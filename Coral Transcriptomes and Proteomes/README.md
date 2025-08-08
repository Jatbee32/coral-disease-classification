# Coral Transcriptome and Proteome Repository
This folder contains the metrics for the transcriptomes used in this project to classify coral diseases based on gene expression. Below is Table 1 from the [DOI](https://www.researchsquare.com/article/rs-5005833/v1) with the necessary transcriptome metrics for coral species and algal endosymbionts. Fasta files generated from this project can be available upon request from Emily Van Buren at emilywvanburen@outlook.com

## Table 1: Transcriptome metrics for coral species and algal endosymbionts

| Species  |  Region  | Disease Study |  Previously Published   | Type   | No. Contigs   | Percentage |  Complete & Single Copy  | Complete & Duplicate  | Fragments   | Missing  | N50  | Percent Annotated  | 
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
|  *C.natans*	  |  USVI	  |  Multi-disease|  	No  |   de novo  |  32,772  |  85%  |  689  |  121  |  38  |  106  |  7,282  |  35%  |
|  *M.cavernosa*  |  USVI  |  Multi-disease  |  No  |  de novo  |  26,063  |  72%  |  581  |  109  |  48  |  216  |  5,475  |  38%  |
|  *O.annularis*  |  USVI  |  Multi-disease  |  No  |  de novo  |  39,725  |  87%  |  697  |  133  |  42  |  82  |  8,524  |  32%  |
|  *O. faveolata*  |  USVI  |  WP  |  No  |  de novo  |  41,110  |  85%  |  670  |  141  |  56  |  87  |  8,677  |  32%  |
|  *S.siderea*  |  USVI  |  WP  |  No  |  de novo  |  33,495  |  70%  |  590  |  75  |  111  |  178  |  7,675  |  37%  |
|  *P.strigosa*  |  USVI  |  SCTLD  |  [*Beavers et al 2023*](10.1038/s41467-023-38612-4)  |  de novo  |  23,116  |  74%  |  603  |  104  |  79  |  192  |  4,970  |  61%  |
|  *P.asteroides*  |  Bermuda  |  Gene-Model  |  [*Wong and Putnam YEAR*](10.46471/gigabyte.65)  |  gene-model  |  64,636  |  80%  |  664  |  95  |  115  |  80  |  14,191  |  50%  |
|  *S.CassKB8*  |  |  NA  |	[*Bayer et al. YEAR*]()  |  de novo  |  72,152  |  |  123  |  6  |  39  |  87  |  17,845  |  NA  |
|  *B.minutum*  |  |  NA  |  [*Parkinson et al. YEAR*]()  |  de novo  |  51,199  |  |  172  |  6  |  19  |  58  |  11,053  |  NA  |
|  *C.goreui*  |  |  NA  |  [*Davies et al. YEAR*]()  |  de novo  |  65,838  |  |  110  |  66  |  18  |  61  |  18,032  |  NA  |
|  *D.trenchii*  |  |  NA  |  [*Bellantouono et al. YEAR*]()  |  de novo  |  82,273  |  |  173  |  13  |  15  |  54  |  17,347  |  NA  |



**Table 1: Transcriptome metrics for coral species and algal endosymbionts.** Coral host transcriptome assembly metrics are based on metazoan reference, and Symbiodiniaceae transcriptome assembly metrics are based on eukaryote reference in BUSCO. Coral species P.strigosa and P. asteroides were sourced from Beavers et al. and Wong and Putnam. Algal endosymbiont transcriptomes were used to filter symbiont reads from samples. Evaluation for these transcriptomes are sourced from Beavers et al., and transcriptomes from S.CassKB8, B.minutum, C.goreui, and D.trenchii were sourced from Bayer et al. (BioProject PRJNA80085), Parkinson et al. (BioProject PRJNA274852), Davies et al. (BioProject PRJNA307543), and Bellantuono et al. (BioProject PRJNA508937). N50 was evaluated through the BBMap program under the Assembly stats script, referencing the median N50 score. The "Percent Annotated" column references the percentage of protein-coding transcripts annotated with Uniprot with an e-value cut-off of 1.0e-6. 												

