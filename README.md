**project Liver Toxicity Predictor** (in progress, to be finished)
# ML Predictor for Drug-induced Liver Injury (DILI)

## Training datasets: 

1. **FDA Drug Induced Liver Injury Rank (DILIrank) Dataset** , https://www.fda.gov/science-research/liver-toxicity-knowledge-base-ltkb/drug-induced-liver-injury-rank-dilirank-dataset.

2. **DL-DILI-Liew** and **DL-DILI-combined** datasets from DL-DILI project http://www.pkumdl.cn:8080/DILIserver/DILIhome.php

3. **Chen Dataset** (LTKB Benchmark Dataset, from Chen M. et al. (2013) *Quantitative Structure-Activity Relationship Models for Predicting Drug-Induced Liver Injury Based on FDA-Approved Drug Labeling Annotation and Using a Large Collection of Drugs*, https://doi.org/10.1093/toxsci/kft189) 

## External validation dataset

**Greene Dataset** (External validation Dataset, from Chen M. et al. (2013) *Quantitative Structure-Activity Relationship Models for Predicting Drug-Induced Liver Injury Based on FDA-Approved Drug Labeling Annotation and Using a Large Collection of Drugs*, https://doi.org/10.1093/toxsci/kft189)


## ML Features *(generated from SMILES)*: 

1.   Morgan Fingerprints
2.   Physico-chemical properties (PaDEL descriptors)



## FILES

**DILI_predictor.ipynb**       Python3 Notebook with scripts

**"Input/ * . * "**     Folder for datasets (training, external validation, final prediction)

**"Output/ * . * "**    Forder for generated output files


## TO DO:
1. Check for chemical bias caused by structural similarity between validation and training datasets, and remove bias with AVE bias script or using Tanimoto Similarity check
2. Hyperparameter tuning and optimisation for predictors
