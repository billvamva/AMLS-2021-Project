# AMLS-2021-Project

This is my repo containing the notebooks used to perform the MRI image classification. The entire submission package can be found on google drive: 
https://drive.google.com/drive/folders/12KpGV0TgMrP91Mb0U7IIRck8c8C2g2Nv?usp=sharing

The notebooks:

1. binary classification: 3 different ml models that perform binary classification and the performance metrics
2. svm classification: Multiclass classification using SVM with HOG and GLCM.
3. cnn classification: a multilayer CNN with FCN classifiction.
4. resnet classification: feature extraction using ResNet50 and classification using SVM.


If the structure of the folder follows the one in the google drive all the files should be ready to run. The CNN also includes a load model function to save time. 

The packages required are

- numpy
- pandas
- sklearn
- skimage
- pillow
- tensorflow
- pickle
- os 
- matplotlib
