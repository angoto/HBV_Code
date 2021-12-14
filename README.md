# HBV_Code
This repository was made to share some code that could be used to parse PubMed Central XML files to gather information about genetic mutations, particularly Hepatitis B Virus. 

1) Main Text: Directory where all the CSV files for figures/tables in the main text of the manuscript can be located. 

2) Notebooks: Directory where code and related files that was used for this project can be located. 

- Clinical_Data_Hypothetical.ipynb: Jupyter Notebook that generates hypothetical clinical data to provide some idea of the data structure used in the original clinical study. 

- clinical_data_hypothetical.csv: CSV file of the hypothetical clinical study dataframe created from Clinical_Data_Hypothetical.ipynb (inside Data sub-directory). 

- DrugBank_Vocabulary_HBV.ipynb: Jupyter Notebook used to generate drug vocabulary related to HBV from DrugBank.ca (https://www.drugbank.ca/) as an example.

- HBV_clinically_approved_DrugBank.txt: Text file containing clinically approved HBV drug from DrugBank.ca created in DrugBank_Vocabulary_HBV.ipynb (inside Data sub-directory). 

- HBV_Mutations_Translation.ipynb: Jupyter Notebook that translates HBV-related genetic mutations obtained from the PubMed Central into a form identical to the clinical study (i.e. amino acid and nucleotide variants). 

- XML_Parsing_PubMed_Central.ipynb: Jupyter Notebook that makes a note of the procedure that I have followed and the representative code that I have used in order to search for cooccurrence of drug and mutation in the same sentence from PubMed Central. 

3) SI: Directory where files relevant to the supplementary information of the manuscript can be located (including csv files). 

- HBV_Supplementary_Information.pdf: Supplementary Information for this work. 
