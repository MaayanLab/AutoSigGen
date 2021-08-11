# AutoSigGen

Notebooks used to generate signatures for the Gene Centric GEO Reverse search (GCGRS) Appyter, which consists of the following:
## Signature Generation Pipeline:
- **0_h5_processing.ipynb** : extraction of bulk RNA-seq data from ARCHS4
- **1_sample_labelling.ipynb** : grouping, labelling, scoring of samples to generate GSM list
- **2_gsms2sig.ipynb** : calculation of signatures using GSM list
- **3_appyter_format_processing.ipynb** : aggregation of signature data for ease of appyter query
- **4_score_extraction.ipynb** : extraction and processing of signature scores
## Gene Set Library Creation for Enrichr:
- **sig2gene_set_library.ipynb** : creation of gene set library from signature data 
