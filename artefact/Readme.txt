Author: Tin Yuet CHUNG
Last Edited: 22 May 2024

This folder of artefact contains:

- Signed CS Fast-Track Ethical Approval Form v5.1
- source data folder
- source code folder

In the source data folder, there are three expert-annotated datasets (2,000 samples each).
Each expert-annotated dataset is a comma-separated value (CSV) file having two columns. 
These include a text column and a binary label column having 0 and 1, 
which indicates the text belongs to one ESG category or not.

Below are the dataset files in the source data folder:
- environmental_2k.csv (Environmental dataset)
- social_2k.csv (Social dataset)
- governance_2k.csv (Governance dataset)

The source code folder contains the source code/folders:

- preprocess_esg_data.ipynb 
(This is a Jupyter notebook written in python to change the label columns of the datasets
E.g. it changes the label of environmental_2k.csv from 0/1 to 'Not Environmental'/'Environmental'.
The labels in other datasets are processed in a similar manner and saved to csv files.)

- llama2 
(This folder contains three Jupyter notebooks written in python to 
fine-tune Llama 2 and evaluate it for its original and fined-tuned model,
for E, S, G Text Classification respectively:
- Fine-tune Llama 2 for Text Classification-Environmental.ipynb
- Fine-tune Llama 2 for Text Classification-Social.ipynb
- Fine-tune Llama 2 for Text Classification-Governance.ipynb)

- Classical ML
(This folder contains three Jupyter notebooks written in python to 
build SVM and XGBoost classifiers and evaluate them for E, S, G Text Classification respectively:
- SVM, XGBoost Text Classification-Environmental.ipynb
- SVM, XGBoost Text Classification-Social.ipynb
- SVM, XGBoost Text Classification-Governance.ipynb)

- Finbert-esg
(This folder contains three Jupyter notebooks written in python to 
evaluate Finbert-esgclassifiers for E, S, G Text Classification respectively:
- Evaluate FinBERT-ESG  for Text Classification-Environmental.ipynb
- Evaluate FinBERT-ESG  for Text Classification-Social.ipynb
- Evaluate FinBERT-ESG  for Text Classification-Governance.ipynb)