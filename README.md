# Biophysics 206 Final Project 
## Uncover copy number associative genetic signatures via single cell RNA sequencing

### Project synopsis: 

Data availability : https://singlecell.broadinstitute.org/single_cell/study/SCP542/pan-cancer-cell-line-heterogeneity

### Data pre-procesing :
- Single cell RNA-seq data preprocessing: [preprocssing script](https://github.com/sanju99/biophys206_finalProject/blob/main/ccle_umi_preprocess.ipynb)
- Bullk RNA-seq data preprocessing: 

### Copy number alteration calling method: 
- Single cell RNA-seq copy number alteration: [single cell copy number calling](https://github.com/sanju99/biophys206_finalProject/blob/main/single_cell_CNA.ipynb)
  - Data reference: data directory
- Bullk RNA-seq copy number alteration: 

### Systematic characterization of single cell copy number alteration and expression-based clusters: 
- Single cell RNA-seq based approach:
  1. Identify cell lines with CNA based subclones: [CNA cluster filter](https://github.com/sanju99/biophys206_finalProject/blob/main/CNA_cluster_filter.ipynb) 
  2. Identify GMM clusters based on chromosomal arm CNA: [GMM cluster](https://github.com/sanju99/biophys206_finalProject/blob/main/chromosomal_arm_gmm_cluster.ipynb)
  3. Identify genetic programs based on leiden clustering and Bayesian non-negative factorization matrix: [genetic programs enriched in CNA subclones](https://github.com/sanju99/biophys206_finalProject/blob/main/gene_expression_signature_comp_cna.ipynb)  

