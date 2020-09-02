 # Multidomain genome recovering (MUDOGER)
 
 ![](https://github.com/EfthymisF/folder-scripts/blob/master/index.png)
 
 The MUDOGER is a pipeline which was developed for the metagenomic analysis of data from Prokaryotes, Viruses and Eykaryotes . For this purpose, MUDOGER combines the 
 utillization of known analytical pipelines: **Metawrap, Virsorter, Virfinder, Vibrant and Eykarep**
 

## MUDOGER Workflow

* **(1)** Trimming of the Metagenomic library and removal of all the host reads by running  metaWRAP-Read_qc
* **(2)** Assembly of the clean metagenomic reads produced in **(1)** by running metaWRAP-Assembly module
* **(3)** Bin extraction with MaxBin2, metaBAT2, and CONCOCT  
* **(4)** Unification of multiple binning prediction into an advanced bin set (Bin refinement)
* **(5)** Quality control using cCheckM
* **(6)** reassemblethe final annotation with PROKKA.


Recovery of viral metagenomes using Virfinder, Virsorter and Vibrant for the prediction of viral sequences.  Then, the protein for each contig was predicted by 

Prodigal and the proteins are identified by Blastp

# OVERVIEW OF THE MUDOGER

* **Installation** 
* **Quality control:** Trimming of the reads and removal of possible host reads
* **Assembly:** Assembly of "good quality" sequences
* **METAWRAP pipeline:** R: Metagenomic analysis of prokaryotic genomes
* **VirFinder, VirSorter, Vibrant pipelines:** Metagenomic analysis of viral sequences 
* **EykRep pipeline:** Metagenomic analysis of Eykaryotic genomes
 
 
 In the pre-processing modules the reads are trimming and any read coming from a host is removed and the resulted metagenomic data are assembled 
 In the 
 
