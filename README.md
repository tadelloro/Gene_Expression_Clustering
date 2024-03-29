### Gene Expression Clustering

#### Problem
Gene expression data from different types of cancerous tumor may be used to identify various cancer subtypes, and assess commonalities and differences between them. The number of gene expressions measured usually exceeds the number of observations (or samples) in gene expression datasets. High dimensionality problems such as these require careful application of dimensionality reduction techniques prior to modeling.

#### Business Case
Categorization of cancer subtypes may allow for more specialized research to be performed, as well as promote the development of specialized treatment and diagnosis programs for patients.

#### Jupyter Notebooks and scripts
* Cluster_Analysis.ipynb includes initial data exploration and visualization. Variance threshold filtering is used together with Principal Component Analysis to perform dimensionality reduction prior to clustering. 

#### Dataset
The dataset includes 801 samples from different types of tumor, each with 20531 different RNA-Seq gene expression levels measured via an illumina HiSeq platform.

The dataset may be found here:
* https://archive.ics.uci.edu/ml/machine-learning-databases/00401/

