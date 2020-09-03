 # Multidomain genome recovering (MUDOGER)
 
 ![](https://github.com/EfthymisF/folder-scripts/blob/master/index.png)
 
 The MUDOGER is a pipeline which was developed for the metagenomic analysis of data from Prokaryotes, Viruses and Eykaryotes . For this purpose, MUDOGER combines the 
 utillization of known analytical pipelines: **Metawrap, Virsorter, Virfinder, Vibrant and Eykarep**
 

## MUDOGER Workflow

* **(1)** Trimming of the Metagenomic library and removal of all the host reads by running  metaWRAP-Read_qc

* **(2)** Assembly of the clean metagenomic reads produced in **(1)** by running metaWRAP-Assembly module

* **(3)** Metagenomic analysis of Prokaryotic genomes 
* **(3.1)** Bin extraction with MaxBin2, metaBAT2, and CONCOCT  
* **(3.2)** Unification of multiple binning prediction into an advanced bin set (Bin refinement)  
* **(3.3)** Quality control using cCheckM  
* **(3.4)** Reassemblethe final annotation with PROKKA

* **(4)** Metagenomic analysis of Viral genomes
* **(4.1)** Recovery of viral metagenomes using Virfinder, Virsorter and Vibrant for the prediction of viral sequences, combination of them to a single file and removal of replicates 
* **(4.2)** Prediction of each contig's protein by Prodigal
* **(4.3)** Identification of Proteins by Blastp

* **(5)** Metagenomic analysis of Eykaryotic genomes
* **(5.1)** Classification  of  Eykaryotic genomes with EykRep
* **(5.2)** Use of CONCOCT for binning and filtering of the Eykaryotic sequences by size.
* **(5.3)** Then, genes are predicted by  using the trained GeneMark-ES model and MAKER2.
* **(5.4)** BUSCO is applied for detection of single copy orthologous genes (SCGs) and will estimate the completeness and contamination of Eykaryotic reads
             


# OVERVIEW OF THE MUDOGER

* **Installation** 
* **ReadQC Quality control:** Trimming of the reads and removal of possible host reads
* **Assembly:** Assembly of "good quality" sequences
* **METAWRAP pipeline:**  Metagenomic analysis of prokaryotic genomes
* **Pipelines for viral genomes(VirFinder, VirSorter, Vibrant):** Metagenomic analysis of viral sequences 
* **EykRep pipeline:** Metagenomic analysis of Eykaryotic genomes


# System requirements


# Installation

# Using MUDOGER

# Step 0: Dowloading the libraries

# Step 1: Trimming the reads and removing possible host reads

# Step 2: Assembly of "good quality" sequences

# Step 3:METAWRAP pipeline

# Step 4:Pipelines for viral genomes(VirFinder, VirSorter, Vibrant)

# Step 5:EykRep pipeline 
