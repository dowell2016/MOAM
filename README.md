# MOAM
MOAM leverages biological pathway information for feature construction and inte-grates cross-attention, multi-head attention, and Kolmogorov-Arnold Networks (KAN) for feature learning and classification. The cross-attention mechanism effectively captures dependencies among different omics data, while the multi-head attention mechanism further extracts key features. Additionally, KAN enhances feature repre-sentation through nonlinear transformations. 

# File description
KEGG_pathways, Annotation relationships between genes/miRNA and KEGG pathways. 
brca_data,  breast cancer data.     
lihc_data,  liver cance data.     
mulcmp_lihc.ipynb, lihc_data run code.   
mulcmp_brca.ipynb, brca_data run code.  

# Running environment
python==3.7.16  
sklearn==0.24.2
pandas == 1.1.5  
numpy==1.21.5  
scikit-learn == 0.24.2  
keras==2.2.4  
tensorflow==2.6.0  
shap==0.42.1
matplotlib==3.5.3

# Acknowledgement
part of the code if borrowed form https://github.com/lanbiolab/DeepKEGG and https://github.com/jianglindong93/AUTOSurv
