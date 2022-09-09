### Introduction
Code and data to measure the contribution of RNA stability to the transcriptome regulation during iPSC-derived neurodevelopment. Look up [preprint paper](https://www.biorxiv.org/content/10.1101/2021.12.11.472181v1) for details.

### Data
The *data* folder contains auxiliary sequence data, quantified genes based on pA sites from the polyA_DB 3 database [PMID: 29069441](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5753232/) and quantified microRNAs. 

### R notebooks
1. **process_counts_data.Rmd**

   Estimate fold-changes in transcription rate, steady state abundance and mRNA half-lifes from drosophila normalized gene level counts data. Gene counts were obtained from as a sum of counts from all pA sites of a gene.
2. **counts_analysis.Rmd**

   Visualize mRNA fold-changes and validations.
3. **measure_global_HL.Rmd**

   Average mRNA half-life between cell types based on saturation curve method.
4. **buffering_of_TR.Rmd**

   Buffering of transcription rate changes with mRNA half-life
5. **differential_3UTR_analysis.Rmd**

   Describe differential regulation of mRNA stability between genes isoforms on 3UTR level.
6. **microRNA_analysis.Rmd**

   Normalize endogenous microRNA abundances with spike-in RNA.
7. **process_mouse_data.Rmd**

   Reanalysis of mESC Ago2 and mRNA data from [PMID: 32497496](https://www.sciencedirect.com/science/article/pii/S1097276520303105?via%3Dihub)
