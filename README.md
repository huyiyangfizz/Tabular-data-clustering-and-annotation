# Tabular-data-clustering-and-annotation
Clustering and annotation for each column of data in a structured table  
The project uses tensorflow and sklearn to implement kmeans algorithm for column clustering and linear svm, random forest, and deep learning (sherlock) algorithms for column annotation. The backend framework uses flask integration api. File storage system uses minio.  Use miniconda to manage the package environment.  
Two environments need to be created with miniconda: api(python = 3.10), sherlock(python = 3.7.16).  
First switch to the working directory and configure the environment:  
`conda activate api`  
`pip install -r requirements_api.txt `  
`conda activate sherlock`  
`pip install -r requirements_shelock txt`  
There are some word2vec dictionary files in sherloc that need to be downloaded manually, see mitmedialab/sherlock-project for details.  
set up:  
`python root.py`  
If using the minio to manage files:  
`./minio.sh`
