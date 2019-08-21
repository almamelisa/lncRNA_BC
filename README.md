# lncRNA_BC

#ABSTRACT
It is a repository that contains information about my master's project. The main topic is lincRNA as biomarkers in breast cancer. The main objective is to identificate lincRNA biomarkers by transcriptome analysis

#INTRODUCTION

This repository is divided into 2 kinds of analysis:

1.- Transcriptome Analysis
2.- Exome Analysis


Transcriptome Analysis is for identification of lincRNA over or sub expressed in breast cancer patients who didn't response to neoadjuvant chemotherapy treatment. The main objective for this analysis is to identify the association of this lincRNA with coding genes and how they are involved in chemoresistance mechanisms

In the other hand, the exome analysis is performed with the objective to identify the possible genetic cause of the distortion in coding gene expression profiles in chemoresistance in breast cancer patients, and if it is related to some clinical variables, like molecular subtype or hormonal receptors expression. With this information, we will be able to associate the genetic profile of coding genes to prognostic and prediction in order to provide benefits for patients management.

The final aim of this whole project is to predict functional association between lincRNA and coding genes through bioinformatic analysis and then validate them to identify possible therapeutic targets and panels of biomarkers for prediction and prognostic in breast cancer patients.

#INDEX

1.- Transcriptome analysis
	..\lncRNA_BC\Transcriptome

It contains folders with RNA-Seq data, pipelines and results of the bioinformatic analysis

	1.1 Scripts and pipeline

	..\lncRNA_BC\Transcriptome\Scripts

It contains .R files with functions and scripts for the biomarker identification pipeline, and they are by numerical order of use. The complete pipeline is specified in README.md.

	1.2 RNA-Seq data
	..\lncRNA_BC\Transcriptome\RNASeq

It contains FastQ Files and Quality reports from breast cancer patients. In README.md are described sequencing features. There is organized in to folders
		
		..\lncRNA_BC\Transcriptome\RNASeq\Fastq

It contains all the Fastq files.

		..\lncRNA_BC\Transcriptome\RNASeq\Quality

It contains all the FastQC quality reports in .pdf format.

	1.3 RNA-Seq Grooming

	..\lncRNA_BC\Transcriptome\Groom

It contains the output of RNA-Seq Groomer Script. They are also FastQ files.

	1.4 Sequence alignment

	..\lncRNA_BC\Transcriptome\RNASTAR

It contains the output of RNA-STAR script for alignment. It is divided into 4 folders

		..\lncRNA_BC\Transcriptome\RNASTAR\refgen

it contains the .gtf file of Comprehensive annotation of GENCODEV.7.

		..\lncRNA_BC\Transcriptome\RNASTAR\Readspergene

It contains .tab files, with normalized counts in TPM units of genes

		..\lncRNA_BC\Transcriptome\RNASTAR\log

It contains .log files.

	1.5 Transcripts counts

	..\lncRNA_BC\Transcriptome\Salmon

It contains .tab output files from transcripts counting process.

	1.6 Differential expression analysis

	..\lncRNA_BC\Transcriptome\DESeq2

It contains the output file from DESeq2 analysis () and it also contain the differential expression report in .tab format.

	1.7 Gene Ontology Analysis

	..\lncRNA_BC\Transcriptome\GO

It contains the output of GO analysis

	1.8 Statiscal Analysis

	..\lncRNA_BC\Transcriptome\STATS

It contains the output of clinical value analysis. It is divided in 5 folders:

		..\lncRNA_BC\Transcriptome\STATS\ROC

It contains the output of ROC curve analysis

		..\lncRNA_BC\Transcriptome\STATS\CHI

It contains the .tab file from Chi Square analysis

		..\lncRNA_BC\Transcriptome\STATS\LOGREG

It contains the .tab output file from logistic regression

		..\lncRNA_BC\Transcriptome\STATS\ODDS

It contains the .txt output file from Odds Ratio analysis

		..\lncRNA_BC\Transcriptome\STATS\CORR

It contains the .txt output file from correlation analysis

	1.9 Graphical Analysis

	..\lncRNA_BC\Transcriptome\Graphs

It contains all the graphical results from the DESeq2 analysis. It is divided in 5 folders:

		..\lncRNA_BC\Transcriptome\Graphs\HM

It contains heatmaps

		..\lncRNA_BC\Transcriptome\Graphs\PCA

It contains PCA plots and the output file from PCA analysis (.tab)

		..\lncRNA_BC\Transcriptome\Graphs\VP

It contains Volcano plots

		..\lncRNA_BC\Transcriptome\Graphs\Bar

It contains barplots

		..\lncRNA_BC\Transcriptome\Graphs\Box

It contains boxplots

	2.0 Clinical information

	..\lncRNA_BC\Transcriptome\Clinic

It contains in .tab and .txt files clinical information about patients.


	3.0 Network Analysis

	..\lncRNA_BC\Transcriptome\NetAnalysis

It contains the output of gene network analysis.

2.- Exome Analysis

	..\lncRNA_BC\Exome

It contains folders with exome sequencing data, analysis and results

	1.0 Exome data

	..\lncRNA_BC\Exome\SeqData

It contains Fasta files and quality controls. Is divided into 3 folders:

		..\lncRNA_BC\Exome\SeqData\Fasta

It contains Fasta files

		..\lncRNA_BC\Exome\SeqData\QualityRep

It contains quality reports

		..\lncRNA_BC\Exome\SeqData\QualityCtrl

It contains quality control files from Call variant analysis

	1.1 Alignment

	..\lncRNA_BC\Exome\Alignment

It contains alignment files and in a subfolder there is located the reference genome
		
		..\lncRNA_BC\Exome\Alignment\Ref

	1.2 Variants calling

	..\lncRNA_BC\Exome\Var

It contains all the output files from variant analysis

	1.3 False positive clear

	..\lncRNA_BC\Exome\Clean

It contains the output files from filtering

	1.4 Graphical analysis

	..\lncRNA_BC\Exome\Graphs

It contains graphical results

#APENDIX 1

Selected topics of Bioinformatics

	..\lncRNA_BC\STB

This folders contains activities from our course.

#END

