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
P5.1 = Patient-5_R1_001
P5.2 = Patient-5_R2_001
P6.1 = Patient-6_R1_001
P6.2 = Patient-6_R2_001
P7.1 = Patient-7_R1_001
P7.2 = Patient-7_R2_001
P8.1 = Patient-8_R1_001
P8.2 = Patient-8_R2_001
P9.1 = Patient-9_R1_001
P9.2 = Patient-9_R2_001
P10.1 = Patient-10_R1_001
P10.2 = Patient-10_R2_001
P11.1 = Patient-11_R1_001
P11.2 = Patient-11_R2_001
P12.1 = Patient-12_R1_001
P12.2 = Patient-12_R2_001
P13.1 = Patient-13_R1_001
P13.2 = Patient-13_R2_001
P14.1 = Patient-14_R1_001
P14.2 = Patient-14_R2_001
P15.1 = Patient-15_R1_001
P15.2 = Patient-15_R2_001
P16.1 = Patient-16_R1_001
P16.2 = Patient-16_R2_001
P17.1 = Patient-17_R1_001
P17.2 = Patient-17_R2_001
P18.1 = Patient-18_R1_001
P18.2 = Patient-18_R2_001
P19.1 = Patient-19_R1_001
P19.2 = Patient-19_R2_001
P20.1 = Patient-20_R1_001
P20.2 = Patient-20_R2_001
P21.1 = Patient-21_R1_001
P21.2 = Patient-21_R2_001
P22.1 = Patient-22_R1_001
P22.2 = Patient-22_R2_001
P23.1 = Patient-23_R1_001
P23.2 = Patient-23_R2_001
P24.1 = Patient-24_R1_001
P24.2 = Patient-24_R2_001
P25.1 = Patient-25_R1_001
P25.2 = Patient-25_R2_001
P26.1 = Patient-26_R1_001
P26.2 = Patient-26_R2_001
P27.1 = Patient-27_R1_001
P27.2 = Patient-27_R2_001
P28.1 = Patient-28_R1_001
P28.2 = Patient-28_R2_001
P29.1 = Patient-29_R1_001
P29.2 = Patient-29_R2_001
P30.1 = Patient-30_R1_001
P30.2 = Patient-30_R2_001

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
p5: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P5.1}.fastq.gz ${WHERE}/${P5.2}.fastq.gz
p6: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P6.1}.fastq.gz ${WHERE}/${P6.2}.fastq.gz
p7:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P7.1}.fastq.gz ${WHERE}/${P7.2}.fastq.gz
p8: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P8.1}.fastq.gz ${WHERE}/${P8.2}.fastq.gz
p9: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P9.1}.fastq.gz ${WHERE}/${P9.2}.fastq.gz
p10: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P10.1}.fastq.gz ${WHERE}/${P10.2}.fastq.gz
p11: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P11.1}.fastq.gz ${WHERE}/${P11.2}.fastq.gz
p12:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P12.1}.fastq.gz ${WHERE}/${P12.2}.fastq.gz
p13:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P13.1}.fastq.gz ${WHERE}/${P13.2}.fastq.gz
p14:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P14.1}.fastq.gz ${WHERE}/${P14.2}.fastq.gz
p15:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P15.1}.fastq.gz ${WHERE}/${P15.2}.fastq.gz
p16:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P16.1}.fastq.gz ${WHERE}/${P16.2}.fastq.gz
p17:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P17.1}.fastq.gz ${WHERE}/${P17.2}.fastq.gz
p18:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P18.1}.fastq.gz ${WHERE}/${P18.2}.fastq.gz
p19:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P19.1}.fastq.gz ${WHERE}/${P19.2}.fastq.gz
p20:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P20.1}.fastq.gz ${WHERE}/${P20.2}.fastq.gz
p21: 
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P21.1}.fastq.gz ${WHERE}/${P21.2}.fastq.gz
p22:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P22.1}.fastq.gz ${WHERE}/${P22.2}.fastq.gz
p23:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P23.1}.fastq.gz ${WHERE}/${P23.2}.fastq.gz
p24:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P24.1}.fastq.gz ${WHERE}/${P24.2}.fastq.gz
p25:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P25.1}.fastq.gz ${WHERE}/${P25.2}.fastq.gz
p26:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P26.1}.fastq.gz ${WHERE}/${P26.2}.fastq.gz
p27:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P27.1}.fastq.gz ${WHERE}/${P27.2}.fastq.gz
p28:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P28.1}.fastq.gz ${WHERE}/${P28.2}.fastq.gz
p29:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P29.1}.fastq.gz ${WHERE}/${P29.2}.fastq.gz
p30:
	${TRIMGALORE}/trim_galore --paired --gzip --retain_unpaired --trim1 --fastqc --fastqc_args "--outdir ${WHERE}/fastqc" -o ${WHERE}/galore --path_to_cutadapt ${CUTADAPT} ${WHERE}/${P30.1}.fastq.gz ${WHERE}/${P30.2}.fastq.gz
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
p5_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P5.1}_val_1.fq.gz  > p5_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P5.2}_val_2.fq.gz  > p5_2.sai
p6_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P6.1}_val_1.fq.gz  > p6_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P6.2}_val_2.fq.gz  > p6_2.sai
p7_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P7.1}_val_1.fq.gz  > p7_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P7.2}_val_2.fq.gz  > p7_2.sai
p8_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P8.1}_val_1.fq.gz  > p8_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P8.2}_val_2.fq.gz  > p8_2.sai
p9_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P9.1}_val_1.fq.gz  > p9_1.sai
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P9.2}_val_2.fq.gz  > p9_2.sai
p10_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P10.1}_val_1.fq.gz  > p10_1.sai	
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P10.2}_val_2.fq.gz  > p10_2.sai
p11_2.sai: 
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P11.1}_val_1.fq.gz  > p11_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P11.2}_val_2.fq.gz  > p11_2.sai
p12_2.sai: 
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P12.1}_val_1.fq.gz  > p12_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P12.2}_val_2.fq.gz  > p12_2.sai
p13_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P13.1}_val_1.fq.gz  > p13_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P13.2}_val_2.fq.gz  > p13_2.sai
p14_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P14.1}_val_1.fq.gz  > p14_1.sai       
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P14.2}_val_2.fq.gz  > p14_2.sai
p15_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P15.1}_val_1.fq.gz  > p15_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P15.2}_val_2.fq.gz  > p15_2.sai
p16_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P16.1}_val_1.fq.gz  > p16_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P16.2}_val_2.fq.gz  > p16_2.sai
p17_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P17.1}_val_1.fq.gz  > p17_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P17.2}_val_2.fq.gz  > p17_2.sai
p18_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P18.1}_val_1.fq.gz  > p18_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P18.2}_val_2.fq.gz  > p18_2.sai
p19_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P19.1}_val_1.fq.gz  > p19_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P19.2}_val_2.fq.gz  > p19_2.sai
p20_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P20.1}_val_1.fq.gz  > p20_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P20.2}_val_2.fq.gz  > p20_2.sai
p21_2.sai: 
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P21.1}_val_1.fq.gz  > p21_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P21.2}_val_2.fq.gz  > p21_2.sai
p22_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P22.1}_val_1.fq.gz  > p22_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P22.2}_val_2.fq.gz  > p22_2.sai
p23_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P23.1}_val_1.fq.gz  > p23_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P23.2}_val_2.fq.gz  > p23_2.sai
p24_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P24.1}_val_1.fq.gz  > p24_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P24.2}_val_2.fq.gz  > p24_2.sai
p25_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P25.1}_val_1.fq.gz  > p25_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P25.2}_val_2.fq.gz  > p25_2.sai
p26_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P26.1}_val_1.fq.gz  > p26_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P26.2}_val_2.fq.gz  > p26_2.sai
p27_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P27.1}_val_1.fq.gz  > p27_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P27.2}_val_2.fq.gz  > p27_2.sai
p28_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P28.1}_val_1.fq.gz  > p28_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P28.2}_val_2.fq.gz  > p28_2.sai
p29_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P29.1}_val_1.fq.gz  > p29_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P29.2}_val_2.fq.gz  > p29_2.sai
p30_2.sai:
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P30.1}_val_1.fq.gz  > p30_1.sai        
	bwa aln ${BWAINDEX}/genome.fa  ${WHERE}/galore/${P30.2}_val_2.fq.gz  > p30_2.sai

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
p5.sam: p5_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p5_1.sai p5_2.sai ${WHERE}/galore/${P5.1}_val_1.fq.gz ${WHERE}/galore/${P5.2}_val_2.fq.gz > p5.sam
p6.sam:	p6_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p6_1.sai p6_2.sai ${WHERE}/galore/${P6.1}_val_1.fq.gz ${WHERE}/galore/${P6.2}_val_2.fq.gz > p6.sam
p7.sam: p7_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p7_1.sai p7_2.sai ${WHERE}/galore/${P7.1}_val_1.fq.gz ${WHERE}/galore/${P7.2}_val_2.fq.gz > p7.sam
p8.sam: p8_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p8_1.sai p8_2.sai ${WHERE}/galore/${P8.1}_val_1.fq.gz ${WHERE}/galore/${P8.2}_val_2.fq.gz > p8.sam
p9.sam: p9_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p9_1.sai p9_2.sai ${WHERE}/galore/${P9.1}_val_1.fq.gz ${WHERE}/galore/${P9.2}_val_2.fq.gz > p9.sam
p10.sam: p10_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p10_1.sai p10_2.sai ${WHERE}/galore/${P10.1}_val_1.fq.gz ${WHERE}/galore/${P10.2}_val_2.fq.gz > p10.sam
p11.sam: p11_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p11_1.sai p11_2.sai ${WHERE}/galore/${P11.1}_val_1.fq.gz ${WHERE}/galore/${P11.2}_val_2.fq.gz > p11.sam
p12.sam: p12_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p12_1.sai p12_2.sai ${WHERE}/galore/${P12.1}_val_1.fq.gz ${WHERE}/galore/${P12.2}_val_2.fq.gz > p12.sam
p13.sam: p13_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p13_1.sai p13_2.sai ${WHERE}/galore/${P13.1}_val_1.fq.gz ${WHERE}/galore/${P13.2}_val_2.fq.gz > p13.sam
p14.sam: p14_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p14_1.sai p14_2.sai ${WHERE}/galore/${P14.1}_val_1.fq.gz ${WHERE}/galore/${P14.2}_val_2.fq.gz > p14.sam
p15.sam: p15_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p15_1.sai p15_2.sai ${WHERE}/galore/${P15.1}_val_1.fq.gz ${WHERE}/galore/${P15.2}_val_2.fq.gz > p15.sam
p16.sam: p16_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p16_1.sai p16_2.sai ${WHERE}/galore/${P16.1}_val_1.fq.gz ${WHERE}/galore/${P16.2}_val_2.fq.gz > p16.sam
p17.sam: p17_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p17_1.sai p17_2.sai ${WHERE}/galore/${P17.1}_val_1.fq.gz ${WHERE}/galore/${P17.2}_val_2.fq.gz > p17.sam
p18.sam: p18_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p18_1.sai p18_2.sai ${WHERE}/galore/${P18.1}_val_1.fq.gz ${WHERE}/galore/${P18.2}_val_2.fq.gz > p18.sam
p19.sam: p19_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p19_1.sai p19_2.sai ${WHERE}/galore/${P19.1}_val_1.fq.gz ${WHERE}/galore/${P19.2}_val_2.fq.gz > p19.sam
p20.sam: p20_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p20_1.sai p20_2.sai ${WHERE}/galore/${P20.1}_val_1.fq.gz ${WHERE}/galore/${P20.2}_val_2.fq.gz > p20.sam
p21.sam: p21_2.sai 
	bwa sampe ${BWAINDEX}/genome.fa p21_1.sai p21_2.sai ${WHERE}/galore/${P21.1}_val_1.fq.gz ${WHERE}/galore/${P21.2}_val_2.fq.gz > p21.sam
p22.sam: p22_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p22_1.sai p22_2.sai ${WHERE}/galore/${P22.1}_val_1.fq.gz ${WHERE}/galore/${P22.2}_val_2.fq.gz > p22.sam
p23.sam: p23_2.sai 
	bwa sampe ${BWAINDEX}/genome.fa p23_1.sai p23_2.sai ${WHERE}/galore/${P23.1}_val_1.fq.gz ${WHERE}/galore/${P23.2}_val_2.fq.gz > p23.sam
p24.sam: p24_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p24_1.sai p24_2.sai ${WHERE}/galore/${P24.1}_val_1.fq.gz ${WHERE}/galore/${P24.2}_val_2.fq.gz > p24.sam
p25.sam: p25_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p25_1.sai p25_2.sai ${WHERE}/galore/${P25.1}_val_1.fq.gz ${WHERE}/galore/${P25.2}_val_2.fq.gz > p25.sam
p26.sam: p26_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p26_1.sai p26_2.sai ${WHERE}/galore/${P26.1}_val_1.fq.gz ${WHERE}/galore/${P26.2}_val_2.fq.gz > p26.sam
p27.sam: p27_2.sai 
	bwa sampe ${BWAINDEX}/genome.fa p27_1.sai p27_2.sai ${WHERE}/galore/${P27.1}_val_1.fq.gz ${WHERE}/galore/${P27.2}_val_2.fq.gz > p27.sam
p28.sam: p28_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p28_1.sai p28_2.sai ${WHERE}/galore/${P28.1}_val_1.fq.gz ${WHERE}/galore/${P28.2}_val_2.fq.gz > p28.sam
p29.sam: p29_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p29_1.sai p29_2.sai ${WHERE}/galore/${P29.1}_val_1.fq.gz ${WHERE}/galore/${P29.2}_val_2.fq.gz > p29.sam
p30.sam: p30_2.sai
	bwa sampe ${BWAINDEX}/genome.fa p30_1.sai p30_2.sai ${WHERE}/galore/${P30.1}_val_1.fq.gz ${WHERE}/galore/${P30.2}_val_2.fq.gz > p30.sam

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
p5.bam: p5.sam
	samtools import ${HG}/genome.fa.fai p5.sam p5.bam
p6.bam: p6.sam
	samtools import ${HG}/genome.fa.fai p6.sam p6.bam
p7.bam: p7.sam	
	samtools import ${HG}/genome.fa.fai p7.sam p7.bam
p8.bam: p8.sam	
	samtools import ${HG}/genome.fa.fai p8.sam p8.bam
p9.bam: p9.sam
	samtools import ${HG}/genome.fa.fai p9.sam p9.bam
p10.bam: p10.sam
	samtools import ${HG}/genome.fa.fai p10.sam p10.bam
p11.bam: p11.sam 
	samtools import ${HG}/genome.fa.fai p11.sam p11.bam
p12.bam: p12.sam 
	samtools import ${HG}/genome.fa.fai p12.sam p12.bam
p13.bam: p13.sam 
	samtools import ${HG}/genome.fa.fai p13.sam p13.bam
p14.bam: p14.sam
	samtools import ${HG}/genome.fa.fai p14.sam p14.bam
p15.bam: p15.sam
	samtools import ${HG}/genome.fa.fai p15.sam p15.bam
p16.bam: p16.sam 
	samtools import ${HG}/genome.fa.fai p16.sam p16.bam
p17.bam: p17.sam 
	samtools import ${HG}/genome.fa.fai p17.sam p17.bam
p18.bam: p18.sam 
	samtools import ${HG}/genome.fa.fai p18.sam p18.bam
p19.bam: p19.sam
	samtools import ${HG}/genome.fa.fai p19.sam p19.bam
p20.bam: p20.sam
	samtools import ${HG}/genome.fa.fai p20.sam p20.bam
p21.bam: p21.sam
	samtools import ${HG}/genome.fa.fai p21.sam p21.bam
p22.bam: p22.sam
	samtools import ${HG}/genome.fa.fai p22.sam p22.bam
p23.bam: p23.sam
	samtools import ${HG}/genome.fa.fai p23.sam p23.bam
p24.bam: p24.sam
	samtools import ${HG}/genome.fa.fai p24.sam p24.bam
p25.bam: p25.sam
	samtools import ${HG}/genome.fa.fai p25.sam p25.bam
p26.bam: p26.sam
	samtools import ${HG}/genome.fa.fai p26.sam p26.bam
p27.bam: p27.sam
	samtools import ${HG}/genome.fa.fai p27.sam p27.bam
p28.bam: p28.sam
	samtools import ${HG}/genome.fa.fai p28.sam p28.bam
p29.bam: p29.sam
	samtools import ${HG}/genome.fa.fai p29.sam p29.bam
p30.bam: p30.sam
	samtools import ${HG}/genome.fa.fai p30.sam p30.bam
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
p5.sorted.bam: 
	samtools sort -T p5.sorted -o p5.sorted.bam p5.bam
	samtools index p5.sorted.bam
p6.sorted.bam:  
	samtools sort -T p6.sorted -o p6.sorted.bam p6.bam
	samtools index p6.sorted.bam
p7.sorted.bam:  
	samtools sort -T p7.sorted -o p7.sorted.bam p7.bam
	samtools index p7.sorted.bam
p8.sorted.bam:  
	samtools sort -T p8.sorted -o p8.sorted.bam p8.bam	
	samtools index p8.sorted.bam
p9.sorted.bam: 
	samtools sort -T p9.sorted -o p9.sorted.bam p9.bam
	samtools index p9.sorted.bam
p10.sorted.bam: p10.bam
	samtools sort -T p10.sorted -o p10.sorted.bam p10.bam
	samtools index p10.sorted.bam
p11.sorted.bam: p11.bam 
	samtools sort -T p11.sorted -o p11.sorted.bam p11.bam
	samtools index p11.sorted.bam
p12.sorted.bam: p12.bam 
	samtools sort -T p12.sorted -o p12.sorted.bam p12.bam
	samtools index p12.sorted.bam
p13.sorted.bam: p13.bam
	samtools sort -T p13.sorted -o p13.sorted.bam p13.bam
	samtools index p13.sorted.bam
p14.sorted.bam: p14.bam 
	samtools sort -T p14.sorted -o p14.sorted.bam p14.bam
	samtools index p14.sorted.bam
p15.sorted.bam: p15.bam
	samtools sort -T p15.sorted -o p15.sorted.bam p15.bam
	samtools index p15.sorted.bam
p16.sorted.bam: p16.bam 
	samtools sort -T p16.sorted -o p16.sorted.bam p16.bam
	samtools index p16.sorted.bam
p17.sorted.bam: p17.bam
	samtools sort -T p17.sorted -o p17.sorted.bam p17.bam
	samtools index p17.sorted.bam
p18.sorted.bam: p18.bam
	samtools sort -T p18.sorted -o p18.sorted.bam p18.bam
	samtools index p18.sorted.bam
p19.sorted.bam: p19.bam
	samtools sort -T p19.sorted -o p19.sorted.bam p19.bam
	samtools index p19.sorted.bam
p20.sorted.bam: p20.bam
	samtools sort -T p20.sorted -o p20.sorted.bam p20.bam
	samtools index p20.sorted.bam
p21.sorted.bam: p21.bam
	samtools sort -T p21.sorted -o p21.sorted.bam p21.bam
	samtools index p21.sorted.bam
p22.sorted.bam: p22.bam
	samtools sort -T p22.sorted -o p22.sorted.bam p22.bam
	samtools index p22.sorted.bam
p23.sorted.bam: p23.bam
	samtools sort -T p23.sorted -o p23.sorted.bam p23.bam
	samtools index p23.sorted.bam
p24.sorted.bam: p24.bam	
	samtools sort -T p24.sorted -o p24.sorted.bam p24.bam
	samtools index p24.sorted.bam
p25.sorted.bam: p25.bam
	samtools sort -T p25.sorted -o p25.sorted.bam p25.bam
	samtools index p25.sorted.bam
p26.sorted.bam: p26.bam
	samtools sort -T p26.sorted -o p26.sorted.bam p26.bam
	samtools index p26.sorted.bam
p27.sorted.bam: p27.bam
	samtools sort -T p27.sorted -o p27.sorted.bam p27.bam
	samtools index p27.sorted.bam
p28.sorted.bam: p28.bam
	samtools sort -T p28.sorted -o p28.sorted.bam p28.bam
	samtools index p28.sorted.bam
p29.sorted.bam: p29.bam
	samtools sort -T p29.sorted -o p29.sorted.bam p29.bam
	samtools index p29.sorted.bam
p30.sorted.bam: p30.bam
	samtools sort -T p30.sorted -o p30.sorted.bam p30.bam
	samtools index p30.sorted.bam
#=====
#VCF 
#=====
#Diploid as no ploidy is specified 

p1.vcf: p1.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p1.sorted.bam | bcftools call -vmO v -o p1.vcf --threads 2
p2.vcf: p2.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p2.sorted.bam | bcftools call -vmO v -o p2.vcf --threads 2
p3.vcf: p3.sorted.bam 
	samtools mpileup -uf ${BWAINDEX}/genome.fa p3.sorted.bam | bcftools call -vmO v -o p3.vcf --threads 2
p4.vcf: p4.sorted.bam	
	samtools mpileup -uf ${BWAINDEX}/genome.fa p4.sorted.bam | bcftools call -vmO v -o p4.vcf --threads 2
p5.vcf: p5.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p5.sorted.bam | bcftools call -vmO v -o p5.vcf --threads 2
p6.vcf: p6.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p6.sorted.bam | bcftools call -vmO v -o p6.vcf --threads 2
p7.vcf: p7.sorted.bam 
	samtools mpileup -uf ${BWAINDEX}/genome.fa p7.sorted.bam | bcftools call -vmO v -o p7.vcf --threads 2
p8.vcf: p8.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p8.sorted.bam | bcftools call -vmO v -o p8.vcf --threads 2
p9.vcf: p9.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p9.sorted.bam | bcftools call -vmO v -o p9.vcf --threads 2
p10.vcf: p10.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p10.sorted.bam | bcftools call -vmO v -o p10.vcf --threads 2
p11.vcf: p11.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p11.sorted.bam | bcftools call -vmO v -o p11.vcf --threads 2
p12.vcf: p12.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p12.sorted.bam | bcftools call -vmO v -o p12.vcf --threads 2
p13.vcf: p13.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p13.sorted.bam | bcftools call -vmO v -o p13.vcf --threads 2
p14.vcf: p14.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p14.sorted.bam | bcftools call -vmO v -o p14.vcf --threads 2
p15.vcf: p15.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p15.sorted.bam | bcftools call -vmO v -o p15.vcf --threads 2
p16.vcf: p16.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p16.sorted.bam | bcftools call -vmO v -o p16.vcf --threads 2
p17.vcf: p17.sorted.bam	
	samtools mpileup -uf ${BWAINDEX}/genome.fa p17.sorted.bam | bcftools call -vmO v -o p17.vcf --threads 2
p18.vcf: p18.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p18.sorted.bam | bcftools call -vmO v -o p18.vcf --threads 2
p19.vcf: p19.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p19.sorted.bam | bcftools call -vmO v -o p19.vcf --threads 2
p20.vcf: p20.sorted.bam	
	samtools mpileup -uf ${BWAINDEX}/genome.fa p20.sorted.bam | bcftools call -vmO v -o p20.vcf --threads 2
p21.vcf: p21.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p21.sorted.bam | bcftools call -vmO v -o p21.vcf --threads 2
p22.vcf: p22.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p22.sorted.bam | bcftools call -vmO v -o p22.vcf --threads 2
p23.vcf: p23.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p23.sorted.bam | bcftools call -vmO v -o p23.vcf --threads 2
p24.vcf: p24.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p24.sorted.bam | bcftools call -vmO v -o p24.vcf --threads 2
p25.vcf: p25.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p25.sorted.bam | bcftools call -vmO v -o p25.vcf --threads 2
p26.vcf: p26.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p26.sorted.bam | bcftools call -vmO v -o p26.vcf --threads 2
p27.vcf: p27.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p27.sorted.bam | bcftools call -vmO v -o p27.vcf --threads 2
p28.vcf: p28.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p28.sorted.bam | bcftools call -vmO v -o p28.vcf --threads 2
p29.vcf: p29.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p29.sorted.bam | bcftools call -vmO v -o p29.vcf --threads 2
p30.vcf: p30.sorted.bam
	samtools mpileup -uf ${BWAINDEX}/genome.fa p30.sorted.bam | bcftools call -vmO v -o p30.vcf --threads 2
