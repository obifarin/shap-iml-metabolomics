# shap-metabolomics
 
Code base for the study: **"Interpretable machine learning with tree-based shapley additive explanations: application to metabolomics datasets for binary classification."**

[Link to Preprint](https://www.biorxiv.org/content/10.1101/2022.09.19.508550v1)

## Requirements

- __[Anaconda](https://www.anaconda.com/)__
- __[Python >= 3.8.8](https://www.python.org/downloads/)__
- __[Jupyter](https://jupyter.org/install)__


### 1. git repository

Clone local copy of git repository

git clone https://github.com/obifarin/shap-iml-metabolomics

(or use a git GUI client of your choice)

### 2. Environment setup and access jupyter notebooks
Setup python environment (`pls-da-shap.yml`) in the terminal. 

(or use anaconda GUI.)


### 3. Notebook contents

<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>01_Sex_MTBLS404.ipynb</td>
    <td>Discriminating biological sex via urine metabolomics.</td>
  </tr>
  <tr>
    <td>02_HighFatDiet_MTBLS547.ipynb</td>
    <td>The impact of a high-fat diet on bile acids in the cecum.</td>
  </tr>
   <tr>
    <td>03_Adenocarcinoma_ST000369.ipynb</td>
    <td>Detecting Adenocarcinoma via serum metabolomics.</td>
  </tr>
    <tr>
    <td>04-pubmed-metabolomics.ipynb</td>
    <td>Keyword occurrences by year for partial least squares regression, random forest, and gradient boosting in metabolomics publications on PubMed.</td>
  </tr>
</table>

## Code base notes> 

- The anaconda environment for this work: pls-da-shap.yml
- The important models are saved in the folder saved_models.
- PyChemometrics is the folder for the library used in PLS-DA computation for this work. For some reason, some PLS-DA code wouldn't run if you don't have them in the same directory from which you run the code. 
- Data folder contains the raw data used in this study, as prepared by [Mendez et al](https://link.springer.com/article/10.1007/s11306-019-1612-4) in his paper.
