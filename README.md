# DL- Developing a Neural Network Classification Model using Transfer Learning

## AIM
To develop an image classification model using transfer learning with VGG19 architecture for the given dataset.

## DESIGN STEPS
### STEP 1: 
Import required libraries and define image transforms.

### STEP 2: 
Load training and testing datasets using ImageFolder.


### STEP 3: 
Visualize sample images from the dataset.


### STEP 4: 
Load pre-trained VGG19, modify the final layer for binary classification, and freeze feature extractor layers.

### STEP 5: 
Define loss function (BCEWithLogitsLoss) and optimizer (Adam). Train the model and plot the loss curve.


### STEP 6: 
Evaluate the model with test accuracy, confusion matrix, classification report, and visualize predictions.

## PROGRAM

### Name: NISHA D

### Register Number: 212223230143

```python



```

### OUTPUT

## Training Loss, Validation Loss Vs Iteration Plot
![4 1](https://github.com/user-attachments/assets/e607b8d8-29a2-48b0-8dbe-235e245031d3)


## Confusion Matrix
![4 2](https://github.com/user-attachments/assets/4ec95b1f-f30a-4cd9-8291-5416ba66ee8d)


## Classification Report
![4 3](https://github.com/user-attachments/assets/c7ae729f-5641-4ccc-9da8-6f1104500bc2)



### New Sample Data Prediction
![4 4](https://github.com/user-attachments/assets/17dd52b3-54de-4463-97cf-b524641a6ff5)

![4 5](https://github.com/user-attachments/assets/e3233f01-7d3d-4035-9129-57934a195c84)


## RESULT
VGG19 model was fine-tuned and tested successfully. The model achieved good accuracy with correct predictions on sample test images.
