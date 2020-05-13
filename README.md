# NLP on QA Forum
Prediction of the best answers of the questions using a QA forum data, including the texts. \
*Since the data is too large (283MB) to upload on the git, there is only the codes. 
## Data Preparation
- Time data treatment
- Label encoding
- Embedding using Word2Vec
- Down / Upsampling for the umbalanced target variable

## Modelling
- Xgboost: ROC-AUC 84%
- Neural Network (linear stack of layers): Accuracy 92%, MSE 0.08
