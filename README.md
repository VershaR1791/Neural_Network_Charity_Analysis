# Neural_Network_Charity_Analysis

## Overview of the analysis: 
Beks wants to predict whether applicants will be successfully funded by Alphabet Soup based on the data shared by Alphabet Soup's business team of over 34k orgnaizations that received funding over the years. The data will be preprocessed for neural network machine learning; the model will be then vompiled, trained and evaluated and finally the ML model will be optimized.

## Results:

### Data Preprocessing
- The target for Neural Network ML model is **'IS_SUCCESSFUL'**

- The following features are considered for the model **'NAME', 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT'**.

- **'EIN'** is used neither as targets nor features and was removed from the input data.
![image](https://user-images.githubusercontent.com/84694664/141724741-a80436fe-bacd-41a2-a394-f93c7868b837.png)

### Compiling, Training, and Evaluating the Model

- There are 3 hidden layers with several neurons and the model accuracy ws **72.5%**.The first activation function was **'relu'** but the 2nd and 3rd were **'sigmoid'** and the output function was 'sigmoid'. Changing the 2nd and 3rd activation functions to 'sigmoid' also helped boost the accuracy.

![image](https://user-images.githubusercontent.com/84694664/141724849-bc77e723-2c3a-4871-9d66-49449aca4fda.png)

- Yes the target model performance was achieved.

- The model performance increased on converting the NAME column into data points, which has the biggest impact on improving efficiency. It also increased by adding a third layer and using the "sigmoid" activation function for the 2nd and 3rd layer.

## Summary: 
