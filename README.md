# Classification-of-Pnumonia

To open Juputer notebook files go to https://nbviewer.jupyter.org/ then paste there the link of the jupyter notebook you want to open. The reason for this is Github's backend have problem with *.ipynb files. But hey there is alternative *.py file. 

Dataset is taken from https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

This is a binary classification machine learning model. It classifies the exitence of pneumonia from chest X-Ray photographs. All the classification methods are done form scratch in Python. 

Solutions:
1)Transfer Learning(VGG16) + Logistic Regression
2)Transfer Learning(VGG16) + kNN
3)Transfer Learning(VGG16) + PCA + kNN

Transfer Learning part is done in extractor.ipynb
Extracted features matrices are saved after running extractor.ipynb
All the rest is done in main.ipynb.

Enjoy
