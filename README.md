# Distracted Driver Image Classification 

### Problem Statement
State Farm had came up with a competition on [Kaggle](https://www.kaggle.com/c/state-farm-distracted-driver-detection) where it was to detect distracted driver. The image [dataset](https://www.kaggle.com/c/state-farm-distracted-driver-detection/data) had been recreated in a controlled environment and had been labelled into 10 classes. 

## Source code here
### Data Files:
1) cnn.ipynb
2) vgg16.ipynb
3) resnet50.ipynb

### Steps to run our script:
1. Start a kernel on Kaggle
2. Retrieve the dataset from the Kaggle competition 'State Farm Distracted Driver Detection'
3. Code used in cnn.ipynb --> Simple CNN baseline model 
4. Code used in vgg16.ipynb --> VGG16 model
5. Code used in resnet50.ipynb --> ResNet50 model 
6. Change the parameters in Keras ImageDateGenerator for to retrieve multiple different models 
7. Run all models on the testing data and retrieve the predictions 
8. Collate the predictions on an excel where its being used to manually computate the 
ensembling results of the different permutations of the models (this can be better automated)
9. Keep track of the ensembling results by checking against the Kaggle competition private testing submission
