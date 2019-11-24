
This repo contains the Jupyter Notebook for predicting hospital readmission for patients with diabetes using deep learning. For simplicity we will use the train,validation,test splits from a prior project (https://github.com/andrewwlong/diabetes_readmission). 

This uses the dataset from UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008). 

The methodology behind this notebook is explained in my Medium Blog post: 

## Getting Started with `conda` environment

```bash
conda env create -f environment.yml
conda activate diabetes_deep 
python -m ipykernel install --user --name diabetes_deep
```