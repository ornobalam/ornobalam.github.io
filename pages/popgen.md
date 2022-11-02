---
layout: post
title: "I study population genetics. What does that mean?"
permalink: /popgenbasic/
output: 
  html_document
  
---

As I have moved toward having population genetics/genomics as my main technical area of focus, I’ve often found it challenging to communicate (to non-biologist friends and family, and biology undergraduates I used to teach) what exactly it is that scientists in this field do, beyond generalizations like “they use variation between genomes of individuals to reconstruct the evolutionary history of populations”.
  
    
    
This is not a layman’s introduction to population genetics, which is a more than 100-year-old field rich in math, theory, and modeling. You could look here for a simple introduction, and here for a more academic history if you’re interested. More rather, this is an introduction to the basics of what scientists conducting research in this field do, through the lens of publicly available human genome data. (My own research is on the population genetics of domesticated rice, but human population divisions are obviously much more easily recognizable).
  
    
    
The way I see it, what population geneticists do can largely be broken down into three intersecting parts: the data, population genetics theory, and the analytical tools. This introduction will mostly cover the data. I will split this up into two parts, the first a conceptual introduction for the general audience, and the second a look at the data for more technically oriented readers.
  
    
    
Part One: Genomes and how population geneticists use them
  
    
    
To understand what kind of data population geneticists today analyze, let’s first understand what genomes are. All organisms carry DNA inside their cells that encodes their biological functions and physical characteristics. Some characteristics, such as height, can also be influenced by environmental factors like the availability of food. DNA is a polymer, and contains information in the form of sequences of bases, which are represented as the letters A, T, G, and C. In eukaryotic organisms like humans, DNA is typically arranged into multiple chromosomes. Think of a chromosome as a long string of DNA, which is subdivided into functionally distinct smaller stretches of genes and non-coding regions.
  
    
    
Genes are stretches of DNA that are read and translated into proteins inside cells, which carry out major biological functions. For instance, the protein lipase is produced and secreted by cells in the pancreas to be released into the gut to digest fats in our food. This is the DNA sequence of the gene that encodes pancreatic lipase in humans:
  
    
    
The human genome contains around 20,000 genes spread out across 23 pairs of chromosomes. Since there is two of each chromosome (one from each parent), there are two copies of each gene (with the exception of genes carried on the sex chromosomes in males, who have one X and one Y chromosome). But genes make up only around 1.2% of all the chromosomal DNA in humans. Non-coding regions make up the rest. These regions can have no known function, or be involved in determining when, where, and how much of different genes are expressed (that is, translated into their corresponding proteins). This is known as gene regulation, and is the reason pancreatic lipase is not produced in kidney cells, or some people have darker eye color than others due to the production of more pigment.
  
    
    
The total genetic content of an organism, including the genes and non-coding regions spanning all the different chromosomes, is its genome. All life on earth evolved from a common ancestor, and hence all of our biology is encoded in the same language of DNA. Species differ from each other in the composition of their genomes. For instance, humans share ~96% genome similarity with chimpanzees, our closest living relatives.
  
    
    
Differences in genomes accumulate over time due to the interplay of various evolutionary forces, and as populations become isolated from each other. The differences first arise through random mutations (like a change from A to C in a certain position that occurs in a single individual), which can then either disappear, or spread through populations either by chance, or less often, because the mutations provide some survival or reproductive benefit to the individuals harboring them. Individuals carrying an advantageous mutation are likely to pass on their genomes to more offspring, thereby increasingly the frequency of the mutation in the population.
  
    
    
Population genetics is largely concerned with genomic variation that has accumulated over relatively recent timescales, that is, between individuals within and between populations. On an evolutionary timescale, these differences are minor – human individuals on average share ~99.9% genome similarity. But 0.1% of 3 billion bases is 3 million, so we can still get a lot of information about the history of human populations by studying these variant bases.
  
    
    
Human populations that have remained relatively isolated from each other for thousands of years, like East Asians, Western Europeans, and Native Americans, have come to accumulate different frequencies of various mutations. Most of the variation between individuals occurs in non-coding regions, as genes are usually under strong selection to maintain their sequence to preserve the function of the encoded protein. A famous exception to this generalization is the mutation in a hemoglobin gene that causes sickle-cell anemia, which you can read more about here. Let’s now look at a simple example of using genomic variation to make inferences about population history.
  
    
    
You have sampled human individuals from Asia, Europe, and Africa. If a particular genome position is occupied by the base G in all of the sampled individuals, that is not particularly interesting as it does not provide any information about the history of the separate historical populations. You are therefore going to analyze information on genome positions or bases that are variable in at least one population; maybe a certain position is occupied mostly by C in European and Asian individuals, but by A, G, or C in roughly equal proportions in African individuals. These are known as single nucleotide polymorphisms (SNPs, pronounced as “snips”).
  
    
    
The illustration shows four genomic sites for eight individuals across two populations. The arrows represent sites at which there is variation. Within each population, a particular allele may be fixed, like A in the first position in Population 1, or have a certain frequency; for instance, the allele frequency of C at the third position is 25% in Population 1, while the allele frequency of T at the first position is 75% in Population 2. Positions 1 and 3 represent SNPs.
  
    
    
Now, when comparing a set of SNPs across individuals, you find that the diversity of bases is higher among Africans than in Europeans and Asians, and that African individuals differ from each other more often than they do from Europeans and Asians. This means that the African sample contains more genetically divergent individuals, and much of the diversity in Eurasians is a subset of the diversity in Africans. Alongside other lines of population genetic analyses, as well as evidence like fossils, this can be used to support the conclusion that all non-African populations arose from a small subset of an ancestral African population, which is consistent with the Out-of-Africa hypothesis for the peopling of the world.
  
    
      
This was in fact a real study way back in 2002. Note that this is the tip of the iceberg in terms of what population geneticists do with SNP data, and this kind of analysis based on describing patterns of diversity is usually the first step in modern population genetics studies. SNP data can be used to make inferences about evolutionary processes such as migration and selection, and when combined with other kinds of information like the physical characteristics of organisms, and geographical and climate data, can allow powerful reconstructions of past routes of movement, and traits that have come under selection (causing them, for instance, to spread more rapidly than expected by random chance).
  
    
    
Technologies to determine DNA sequences have evolved rapidly over the last two decades. The Human Genome Project, which set out to build a reference human genome from a handful of individuals, took almost 15 years and \$2.7 billion to complete. Today, it costs less than \$600 to sequence the genome of a single individual in a matter of hours, and tens of genomes can be sequenced in the same run on a sequencing machine. This has led to the modern field of genomics, the study of genomes.
  
    
    
Before sequencing became cheap and rapid, population geneticists would often rely on sequences of parts of the genome from a small number of individuals, and before sequencing was invented, on a handful of known or biochemically inferred variants. Smaller samples of fewer variants could often blur or limit the resolution of their analyses. Now, the synthesis of population genetics with genomics has yielded what’s frequently referred to as population genomics, which has already revolutionized, and continues to revolutionize our understanding of human prehistory, plant and animal domestication, and recent evolution of many other species. No population geneticist today goes about their business divorced from the reality of having access to the modern tools, technologies, and large datasets of genomics. Therefore, population genetics and population genomics basically refer to the same thing.
  
    
    
Part Two: A brief, direct look at data types

Equipped with all of this background, let’s look more closely at the actual data. The first step to having analyzable data is to perform the sequencing. This involves extracting and purifying DNA from tissue (or saliva) samples, preparing the DNA samples in an appropriate manner for the sequencing method/machine being used, and running the sequencer. Researchers often take advantage of both publicly available previously sequenced genomes and newly sequenced genomes in their analyses.
  
    
      
Before I go into the data types, I want to introduce the 1000 Genomes Project. The project represents a catalog of human variation, and in its final phase, sequenced more than 2,000 individuals from more than 20 populations across the world.
  
    
    
Sequencing yields FASTQ files containing the raw sequencing reads. Here’s the first few lines of a FASTQ file from the 1000 Genome Project:
  
    
    
The first two reads from a sequencing run of a single human individual. The first, second, and fourth lines for each read represent label, DNA sequence, and quality score, respectively.
This is basically a huge collection of short, often overlapping sequencing reads (during preparation, DNA is fragmented into small pieces, which are then sequenced in parallel). On its own, the FASTQ file provides no information about where in the genome any sequence occurs. For that, we rely on the process of alignment, where these reads are mapped onto a reference genome, which represents a completely assembled genome with genes and non-coding regions appropriately mapped onto chromosomes. The reference genome used for alignment of the 1000 Genomes Project sequencing reads is available here. This is stored in the FASTA format, and looks like this:
  
    
    
This shows the first few lines of the chromosome 1 DNA sequence. N’s represent bases in low-complexity regions, repeat regions etc. The reference fasta file used for alignment contains the DNA sequences for all chromosomes under headers like the one on the first line.
Alignment yields SAM files which contain information on sequence locations and the depth of coverage. SAM files are usually converted into the smaller, non-human-readable BAM files. Up until this step, these steps are common to all forms of genomic data and analyses, including reads from CHIP-seq and RNA-seq (not necessary to know what these are for this article, if you don’t). SAM files look like this:
  
    
    
This is the first few lines, showing information for just one read. More details can be found here.  

The FASTQ files containing the sequencing reads and the aligned BAM files for each sampled individual (represented by the codes HG00096, HG00097, and so on) can be found here.
  
    
    
As discussed above, we are mainly interested in the sites that vary, or SNPs. To that end, BAM files can be converted into VCF files, which exclusively store information on the positions of variant sites (often SNPs) across a set of individuals. Luckily for us, the 1000 Genomes Project makes available the final VCF files generated from the BAM files. The following is part of a VCF file containing variant sites on chromosome 21:
  
    
    
For each variable position, the VCF contains the frequency of the mutant/alternative allele in each superpopulation (EAS = East Asian, EUR = European etc.), and the allelic states of all individuals (0 = Reference, 1 = Alternative). Only one variable position (the 9411239th base of chromosome 21) out of more than a million are shown. In addition, only two individuals are shown (HG00096 and HG00097) but the table extends offscreen to include 2,502 more individuals. Both of these individuals carry the G mutation on both of their copies of chromosome 21. There are also other fields under the INFO column that I have removed (alongside the headers that explain what they mean) for the sake of simplicity.
  
    
    
We can now try to do a simple analysis with a VCF file. Download, if you’d like, a VCF file, as well as associated metadata (for instance, the region or population that each individual belongs to) into your computer using the following lines of code on Ubuntu or some other Linux environment, after setting a working directory. You will have noticed that FASTQ, BAM, and VCF files, tend to be quite large, so I have consciously chosen Chromosome 21 as it constitutes the smallest VCF file. The a.out file is a program (that I acquired using this parser) to convert the VCF file into a simple two-column format for easier import into R. Note that all of the code shown is a slight simplification from this tutorial, which I favored from several available ones online because of its heavy R dependence. If I were doing this for my actual research, I may use different tools.
  
    
    
# download the vcf.gz (compressed vcf) file for chromosome 21
wget http://ftp.ebi.ac.uk/1000g/ftp/release/20130502/ALL.chr21.phase3_shapeit2_mvncall_integrated_v5a.20130502.genotypes.vcf.gz
 
# download metadata (additional information) on individuals
wget http://ftp.ebi.ac.uk/1000g/ftp/technical/working/20130606_sample_info/20130606_g1k.ped
 
# the metadata file above tells you whether an individual is from Bangladesh, Great Britain, China etc.
# we would like to make a broader comparison, and this file contains continental and subcontinental groupings
wget http://ftp.ebi.ac.uk/1000g/ftp/phase3/20131219.populations.tsv
 
# download the a.out file and rename it
wget https://github.com/ornobalam/genomeinquirer/blob/master/a.out?raw=true
mv a.out?raw=true a.out
  
    
    
The above can also be accomplished by going to the http links, and manually downloading the files through your browser.

The following lines of code can be run on Ubuntu. If you manually downloaded files, this code has to be run after setting the folder containing the files as your working directory.
  
    
    
# modify vcf file into a two-column format for efficient import and processing on R
zcat ALL.chr21.phase3_shapeit2_mvncall_integrated_v5a.20130502.genotypes.vcf  | sed /^#/d  | cut  -f '10-' | ./a.out | cut -f '1-2' > vcf_formatted
 
# retrieve the id's of the individuals represented in the vcf file
zcat ALL.chr21.phase3_shapeit2_mvncall_integrated_v5a.20130502.genotypes.vcf.gz  | sed -n /^#CHROM/p | tr '\t' '\n' | tail -n +10 > ids
The remaining code can be run on R. First, install (if needed) and load the required packages, read in the two-column formatted file, and convert it into a matrix.


# load up packages (and install them if needed)
if(!require("Matrix")){
    install.packages("Matrix")
    library(Matrix)
}
if(!require("irlba")){
    install.packages("irlba")
    library(irlba)
}
if(!require("dplyr")){
    install.packages("dplyr")
    library(dplyr)
}
if(!require("ggplot2")){
    install.packages("ggplot2")
    library("ggplot2")
}
 
# read in the two-column formatted table generated from the original vcf file
x = read.table("vcf_formatted", colClasses=c("integer","integer"), fill=TRUE, row.names=NULL)
 
# convert it into a kind of matrix as input for the irlba function later
chr21 = sparseMatrix(i=x[,2], j=x[,1], x=1.0)
 
# check dimensions
print(dim(chr21))
## [1]    2504 1105538
  
    
    
There are 2,504 individuals with 1,105,538 variable sites.
  
    
    
How would you plot the 2,504 individuals on a graph? Note that each site represents a different variable. Principal component analysis or PCA compresses all that variation into a small number of principal components. The first principal component (PC1) explains the highest percentage of variation in the data, PC2 explains the second-highest, and so on. PCAs are best understood by plotting two (sometimes three) of the principal components, which is what we will do for our individuals.
  
    
    
# read in the metadata and take a look at the first few rows
sample_names <- read.delim("20130606_g1k.ped")
head(sample_names)
 
# read in the individual id's
ids = readLines("ids")
 
# extract only the individuals in our dataset from the sample_names metadata dataframe
samples <- sample_names %>% dplyr::filter(IndividualID %in% ids)
 
# read in superpopulation (continental or subcontinental) information
pop = read.table("20131219.populations.tsv",sep="\t",header=TRUE)
 
# create an object with all the population codes that are assigned their respective superpopulation codes
super <- pop[,3]  
names(super) <- pop[,2]  
super <- factor(super)
 
# add a column to the samples dataframe for the superpopulation codes
samples$Superpopulation = super[as.character(samples$Population)]
 
# in our vcf file, the individuals are arranged alphatically, so arrange the individuals in 
# the samples dataframe alphabetically
samples %>% arrange(IndividualID) -> samples
  
    
    
To perform the PCA, we are going to use a tool that allows us to specify how many principal components we want to compute. For the sake of computational speed, we will just do the first two. Since we are doing just two, we won’t know exactly what percentage of the variation is explained by each of the principal components, but the rule that PC1 explains more variation than PC2, which explains more variation than PC3, and so on, still holds.
  
    
    
The left singular vectors (u) for our matrix represent variation between individuals, while the right singular vectors represent variation between sites. We are interested in the former.


# this will be necessary to standardize all the site data
cm = colMeans(chr21)
 
# perform the pca
q = irlba(chr21, nv=2, nu=2, tol=0.1, center=cm)
 
# extract the principal components explaining the variation between individuals and name them as such
pc <- q$u
colnames(pc) <- c("PC1","PC2")
 
# add PC1 and PC2 to our samples dataframe
samples_pc <- cbind(samples,pc)
 
# plot the principal components while coloring the points by superpopulation
ggplot(data = samples_pc, aes(y=PC2, x= PC1,color = Superpopulation))+
  geom_point()
  
    
    
AFR = African, AMR = American, EAS = East Asian, EUR = European, SAS = South Asian
We have to be careful to not overinterpret this plot, but here are a few things we can observe: 1) PC1, which explains most of the variation between individuals largely splits up African subpopulations (AFR) from the rest of the subpopulations, and shows there is more variation between African individuals (points spread out wider across horizontal axis) than between individuals in the other populations. 2) PC2 splits up South Asians (SAS), East Asians (EAS), and Europeans (EUR) quite neatly.
   
     
     
Note that the American populations, sampled from Mesoamerica, South America, and the Caribbean, contain recent ancestry from Africa and Europe, which could perhaps explain their spectrum and overlap with other populations. The African individuals include some African-Americans, who have European ancestry, but removing them does not change the wide distribution of the African individuals. The separation of the rest of the populations from Africans is consistent with divergence since migration out of Africa.
  
    
    
We are only using SNPs on chromosome 21 to cluster individuals here, but using SNPs from the entire genome would likely recapitulate the general trends.
  
    
    
The fact that two populations cluster separately does NOT mean that they share no genetic variation. Individuals that cluster more closely simply share more SNPs or have more similar allele frequencies. It also bears repeating that these clusters are based on the very tiny amount of variation between human individuals, who otherwise share ~99.9% genome similarity. As a final caveat, it is important to note that populations as defined and understood by population geneticists rarely correspond to modern ideas of race and ethnicity. Human populations have historically been very dynamic, and populations we think of as Europeans or Indians have only come to occupy those regions over the last 5,000 years or less. In addition, essentially all modern populations represent mixtures of other populations that migrated into regions at different times. The goal of human population genetics is to understand human evolutionary history and the diversity of human traits, not to derive qualitative conclusions on scientifically unsupported racial classifications.