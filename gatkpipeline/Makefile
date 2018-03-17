BWAINDEX = /data/WHRI-EndocrinePituitaryGroup/sherine/databases/Homo_sapiens/UCSC/hg19/Sequence/BWAIndex
HG =  /data/WHRI-EndocrinePituitaryGroup/sherine/databases/Homo_sapiens/UCSC/hg19/Sequence/WholeGenomeFasta
VEP = /data/home/hhx779/ensembl-vep
ANNOVAR = /data/WHRI-EndocrinePituitaryGroup/software/annovar

TRIMGALORE = /data/home/hhx779/software/TrimGalore-0.4.3
CUTADAPT = /data/home/hhx779/python27-sherine/bin/cutadapt

WHERE = /data/WHRI-EndocrinePituitaryGroup/sherine/somana

P1.1 = Patient-1_R1_001
P1.2 = Patient-1_R2_001
P2.1 = Patient-2_R1_001
P2.2 = Patient-2_R2_001
P3.1 = Patient-3_R1_001
P3.2 = Patient-3_R2_001
P4.1 = Patient-4_R1_001
P4.2 = Patient-4_R2_001

#TRIM ADAPTORS 
#===============
p1: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P1.1}.fastq.gz ${WHERE}/${P1.2}.fastq.gz
p2: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P2.1}.fastq.gz ${WHERE}/${P2.2}.fastq.gz
p3:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P3.1}.fastq.gz ${WHERE}/${P3.2}.fastq.gz
p4: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P4.1}.fastq.gz ${WHERE}/${P4.2}.fastq.gz
#======================================
#Align Fastq files to Reference Genome 
#======================================

p1_2.sai: 
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P1.1}_val_1.fq.gz  > p1_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P1.2}_val_2.fq.gz  > p1_2.sai
p2_2.sai: 
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P2.1}_val_1.fq.gz  > p2_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P2.2}_val_2.fq.gz  > p2_2.sai
p3_2.sai: 
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P3.1}_val_1.fq.gz  > p3_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P3.2}_val_2.fq.gz  > p3_2.sai
p4_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P4.1}_val_1.fq.gz  > p4_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P4.2}_val_2.fq.gz  > p4_2.sai

#============================
#Creating SAM files
#============================

p1.sam: p1_2.sai 
	bwa sampe ${BWAINDEX}/genome.fa p1_1.sai p1_2.sai ${WHERE}/galore/${P1.1}_val_1.fq.gz ${WHERE}/galore/${P1.2}_val_2.fq.gz > p1.sam
p2.sam: p2_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p2_1.sai p2_2.sai ${WHERE}/galore/${P2.1}_val_1.fq.gz ${WHERE}/galore/${P2.2}_val_2.fq.gz > p2.sam
p3.sam: p3_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p3_1.sai p3_2.sai ${WHERE}/galore/${P3.1}_val_1.fq.gz ${WHERE}/galore/${P3.2}_val_2.fq.gz > p3.sam
p4.sam: p4_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p4_1.sai p4_2.sai ${WHERE}/galore/${P4.1}_val_1.fq.gz ${WHERE}/galore/${P4.2}_val_2.fq.gz > p4.sam

#Here  I assume HG has an indexed with sam tools 
#=================================
#SAM to BAM
#=================================
p1.bam: p1.sam 
	samtools import ${HG}/genome.fa.fai p1.sam p1.bam
p2.bam: p2.sam
	samtools import ${HG}/genome.fa.fai p2.sam p2.bam
p3.bam: p3.sam
	samtools import ${HG}/genome.fa.fai p3.sam p3.bam
p4.bam: p4.sam
	samtools import ${HG}/genome.fa.fai p4.sam p4.bam
#==================================
#Sorting
#==================================
p1.sorted.bam:  
	samtools sort -T p1.sorted -o p1.sorted.bam p1.bam
	samtools index p1.sorted.bam
p2.sorted.bam:  
	samtools sort -T p2.sorted -o p2.sorted.bam p2.bam
	samtools index p2.sorted.bam
p3.sorted.bam: 
	samtools sort -T p3.sorted -o p3.sorted.bam p3.bam
	samtools index p3.sorted.bam
p4.sorted.bam: 
	samtools sort -T p4.sorted -o p4.sorted.bam p4.bam
	samtools index p4.sorted.bam



#===========================================
#Mark duplicates 
#===========================================
p1.dedupped.bam: 
	java -Dlog4j.configurationFile="log4j2.xml" -jar ${PICARD}/picard.jar AddOrReplaceReadGroups I=${WHERE}/Aligned.out.sam O=${WHERE}/rg_added_sorted.bam \
	SO=coordinate RGID=@E00461_116.SP1452_S3 RGLB=SP1452_S3 RGPL=ILLUMINA RGPU=@E00461_116_GW170602261_1.SP1452_S3 RGSM=SP1452
	java -Dlog4j.configurationFile="log4j2.xml" -jar ${PICARD}/picard.jar MarkDuplicates I=${WHERE}/rg_added_sorted.bam O=${WHERE}/${P1}.dedupped.bam  CREATE_INDEX=true \
	VALIDATION_STRINGENCY=SILENT M=${WHERE}/output.metrics 
        

#Changed to skip indel realignment 
sp1452.recal_data.table: 
	java -jar ${GATK}/GenomeAnalysisTK.jar \
	-T BaseRecalibrator \
	-R ${hg38}.fasta \
	-I ${WHERE}/${CURRENT}.split.bam \
	-knownSites ${DBSNP} \
	-knownSites ${GOLDINDELS} \
	-o ${WHERE}/${CURRENT}.recal_data.table 

sp1452.post_recal_data.table: 
	java -jar ${GATK}/GenomeAnalysisTK.jar \
	-T BaseRecalibrator \
	-R ${hg38}.fasta \
	-I ${WHERE}/${CURRENT}.split.bam \
	-knownSites ${DBSNP}  \
	-knownSites ${GOLDINDELS} \
	-BQSR ${WHERE}/${CURRENT}.recal_data.table \
	-o ${WHERE}/${CURRENT}.post_recal_data.table 

sp1452.recabliration_plots.pdf: 
	java -jar ${GATK}/GenomeAnalysisTK.jar \
	-T AnalyzeCovariates \
	-R ${hg38}.fasta \
	-before ${WHERE}/${CURRENT}.recal_data.table \
	-after ${WHERE}/${CURRENT}.post_recal_data.table \
	-plots ${WHERE}/${CURRENT}.recalibration_plots.pdf

#Assuming post recabliration is better than before recabliration 

sp1452.bam: 
	java -jar ${GATK}/GenomeAnalysisTK.jar \
	-T PrintReads \
	-R ${hg38}.fasta  \
	-I  ${WHERE}/${CURRENT}.split.bam \
	-BQSR ${WHERE}/${CURRENT}.post_recal_data.table \
	-o ${WHERE}/${CURRENT}.bam
#This is recablirated bam 


sp1452.vcf: 
	java -jar ${GATK}/GenomeAnalysisTK.jar -T HaplotypeCaller -R ${hg38}.fasta -I ${WHERE}/${CURRENT}-recablirated.bam \
	-dontUseSoftClippedBases -stand_call_conf 20.0 -o ${CURRENT}.vcf




