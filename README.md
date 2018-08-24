## A small RNA-seq example data set

This repository contains a small RNA-seq example data set, which may be suitable, e.g., for teaching or for testing workflows. The original data files come from the study by [Himes et al. (2014)](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0099625) (GEO accession number [GSE52778](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52778)). This example data set includes four of the samples from this data set (SRR1039508, SRR1039509, SRR1039512 and SRR1039513), representing Dexamethasone treated and untreated samples from two cell lines. The FASTQ files have been subsetted to include only reads aligning within the first 10M bases of chromosome 1 (of the GRCh38 reference genome). 

In addition to the FASTQ files with the reads, we provide reference annotation files from two sources; Ensembl (release GRCh38.93) and Gencode (v28). For each annotation source, we include a fasta file with the genome sequence, a gtf file with the corresponding gene annotation, and one or more fasta files with transcript sequences. All files were subsetted to include only features from the first 10M bases of chromosome 1. 

### Gencode reference files
The Gencode reference files were downloaded from [https://www.gencodegenes.org/releases/current.html](https://www.gencodegenes.org/releases/current.html). 

- reference/GRCh38.primary_assembly.genome.1.1.10M.fa (genome sequence)
- reference/gencode.v28.transcripts.1.1.10M.fa.gz (transcript sequences)
- reference/gencode.v28.annotation.1.1.10M.gtf (gene annotation)

### Ensembl reference files
The Ensembl reference files were downloaded from [https://www.ensembl.org/info/data/ftp/index.html](https://www.ensembl.org/info/data/ftp/index.html).

- reference/Homo_sapiens.GRCh38.dna.chromosome.1.1.10M.fa (genome sequence)
- reference/Homo_sapiens.GRCh38.cdna.all.1.1.10M.fa.gz (cDNA transcript sequences)
- reference/Homo_sapiens.GRCh38.ncrna.1.1.10M.fa.gz (ncRNA transcript sequences)
- reference/Homo_sapiens.GRCh38.93.1.1.10M.gtf (gene annotation)
