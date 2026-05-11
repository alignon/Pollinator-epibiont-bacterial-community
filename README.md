# Pollinator-epibiont-bacterial-community

**Submitted to Microbial Ecology**

**Manuscript title:** Pollinator species identity and habitat determine epibiont bacterial diversity  

**Authors:** 
- V. Aiko Lignon
- E. Eirian Jones,
- Manpreet K. Dhami,
- Clive Kaiser,
- Flore Mas

**Affiliations:** Lincoln University, Lincoln, New Zealand; Bioeconomy Science Institute - Manaaki Whenua Landcare Research, Lincoln, New Zealand; Bioeconomy Science Institute - Plant & Food Research, Lincoln, New Zealand  

This repository contains the R code to reproduce the analyses and figures for the manuscript above. It includes the pipeline to process 16S rRNA gene amplicons, build `phyloseq` objects, perform community analyses (alpha/beta diversity, beta dispersion, PERMANOVA), identify shared/unique genera (UpSet), and conduct differential abundance testing (DESeq2). 
NOTE: Samples were sequenced across different Illumina sequencing runs and were therefore analysed separately. For this reason, the ASV and taxonomy tables are separated by year.

Data:
- sample metadata (filename: Metadata_Pollinator.csv)
- Amplicon Sequence Variant (ASV) table (filename: 2022_pollinator_asv_table.csv and 2023_pollinator_asv_table.csv)
- Taxonomic assignment table (filename: 2022_pollinator_taxonomy_table.csv and 2023_pollinator_taxonomy_table.csv)
