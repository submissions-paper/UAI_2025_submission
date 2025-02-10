# UAI 2025 Supplemental Material Submission

### This is the submission for UAI 2025

This repository includes UAI_tte_experimentations_categorical_existing_regex_method.ipynb and UAI_tte_experimentations_categorical_original_BERT_v2.ipynb.

The two files contains the derivations, calculations, and experimentions to account for measurement error w.r.t an originally "unknown" and imputed (via LLMs such as BERT or classical ML models using regex) confounder (ex: Smoking Status) in causal effects (specifically risk and odds ratio). It is important to note that due to privacy rules with MIMIC-III and Harvard's n2c2 2006 smoking dataset, it is not possible to show certain components of the processs (ex: data filtering, dataframe generations, model training, etc...). However, some information about the dataframes are given within comments in the notebook, such as number of entries and important feature names to help viewers better understand the flow for causal analysis, especially with creating formula strings. Additionally, pickle files (such as the files containing separate varied error matrices) used for bootstrapping are not included in this notebook, but the process of using them to measure the variance of causal effects is still demonstrated.
