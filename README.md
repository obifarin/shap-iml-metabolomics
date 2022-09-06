# shap-metabolomics

Code base for the paper: Interpretable machine learning with tree-based shapley additive explanations: application to metabolomics datasets for binary classification

## Abstract
Machine learning (ML) models are used in clinical metabolomics studies most notably for biomarker discoveries, to identify metabolites that discriminate between a case and control group. To improve understanding of the underlying biomedical problem and to bolster confidence in these discoveries, model interpretability is germane. In metabolomics, partial least square discriminant analysis (PLS-DA) and its variants are widely used, partly due to the model’s interpretability with the Variable Influence in Projection (VIP) scores, a global interpretable method. Herein, Tree-based Shapley Additive explanations (SHAP), an interpretable ML method grounded in game theory, was used to explain ML models with local explanations properties. In this study ML experiments (binary classification) was conducted for three published metabolomics datasets using PLS-DA, random forests, gradient boosting, and extreme gradient boosting (XGBoost). Using one of the datasets, PLS-DA model was explained using VIP scores, while a tree-based model was interpreted using Tree SHAP. The results show that SHAP has a more explanation depth than PLS-DA’s VIP, making it a powerful method for rationalizing machine learning predictions from metabolomics studies.  

## Code base notes> 

- Older notebooks can be safely ignored for the manuscript, as those are associated to the first version of the manuscript, as it can be found in my PhD thesis. 
- The anaconda environment for this work: pls-da-shap.yml
- The important models are saved in the folder saved_models.
- PyChemometrics is the folder for the library used in PLS-DA computation for this work. For some reason, some PLS-DA code wouldn't run if you don't have them in the same directory from which you run the code. 
- Data folder contains the raw data used in this study, as prepared by Mendez et al in machine learning paper. 
