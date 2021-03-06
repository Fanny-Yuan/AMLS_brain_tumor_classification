# Brain-tumor-classification
  AMLS_21-22 _SN21049888
  
  Final project of AMLS about brain tumor classification. Four models included: KNN, SVM, MLP and CNN (ResNet50). Codes for both binary task and multiclass task. \
  All codes are written with python using jupyter notebook. I put the two machine learning methods in one notebook and the two deep learning methods in another one. Train and test session are all written in the notebooks.
  
If you want to train and test machine learning models, run KNN_SVM.ipynb\
If you want to train or test deep learning models, run MLP_CNN.ipynb

More detailed instructions are written in jupyter notebooks.

## Environments
To run the code, you need:

python 3.x\
sklearn\
pandas\
numpy \
openCV\
tensorflow>=2.3

ATTENTION: all codes are written based on Windows. As most works are done using my CPU except that the training of ResNet is on Google Colab (the model is too large and my CPU cannot handle it). If you want to run the codes on Linux, please change all data paths from '\\' to '/'.

## Train and test
First please follow the step in jupyter notebook to do necessary data processing. \
For machine learning, you should train the model at first, then you may get the same results of mine.\
For deep learning, you can train your own model. But results might be different during each training. You can also choose to test my trained models directly, which are put in the release: https://github.com/Fanny-Yuan/Brain-tumor-classification/releases/tag/models

## Results
Accuracy in the original test set is shown in the table:

| |binary task|multiclass task|
|------|------|------|
|KNN|0.9283|0.875|
|SVM|0.9617|0.8783|
|MLP|1.0|0.7717|
|CNN|1.0|0.96|
