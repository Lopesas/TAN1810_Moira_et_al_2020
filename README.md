# TAN1810 Moira et al 2020 dataset 

**Script and processed data for:**
## Salp blooms drive 5-fold increases in carbon transfer to the deep ocean

Moira Décima, Michael R. Stukel, Scott D. Nodder, Andres Gutiérrez-Rodríguez, Karen E. Selph, Adriana Lopes dos Santos, Karl Safi, Thomas B. Kelly, Fenella Deans, Sergio Morales, Mikel Latasa, Maxim Y. Gorbunov and Matt Pinkerton

All cruise metadata has been deposited at https://issues.pangaea.de/browse/PDI-25764  
Fastq files are under accession number XXXXX. 

###### Directories
The metabarcoding data has been acquired and analyzed separately. 

- Prokaryotic Community 
  - Salp_MS_16S_2020.Rmd: script to treat and analyze prokaryotic sequencing data
  - TAN1810_ASV_abundandce_refSeq.csv: ASV abundance table with ref seqs per ASV. 
 
- Eukaryotic Community  
 - R_sediment_traps
   - TAN1810 sediment traps metabarcoding_AL.Rmd: Script to produce phyloseq files and produce plots
   - colors.xlsx: color assignation for pseudo-class
 - metabarcoding
   - phyloseq_metapr2_asv_set_47_Eukaryota.rda: phyloseq file
   - output files from dada2 analysis



