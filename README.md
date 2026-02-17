# Project_variant_calling
A documentation of the variant_calling technique on CLI, using required tools, such as bowtie2, samtools, bcftools.

Dependencies or packages required: bowtie2, samtools, bcftools

# Bowtie2

To install bowtie2:
```
sudo apt install bowtie2 -y
```
To check version:
```
bowtie2 --version
```
# samtools & bcftools

To install samtools & bcftools:
```
sudo apt install samtools bcftools -y
```

In any case assistance required to run a particular command:
```
bowtie2 --help
```
```
samtools --help
```
```
bcftools --help
```

Install wget, unzip packages if not downloaded before hand using the commands below:
```
sudo apt install wget -y
```
```
sudo apt install unzip -y
```

# To unzip files in the directory
The gunzip command:
```
gunzip example_ref_file.fasta.gz
```
```
gunzip example_fastq_file.fastq.gz
```
