# State Farm Distracted-Driver

## Done using custom CNN model and then using Transfer Learning model by using Mobilenet V2 as my base algorithm. 
Notebook for distracted driver detection 



Given the dataset consisting of driver images in car and corresponding labels for 10 nos. categories (e.g. safe driving, texting, talking etc.)
We have to classify the driver based on these labels.

For Dataser you would need to join this "https://www.kaggle.com/competitions/state-farm-distracted-driver-detection" competition on Kaggle.Either you can download the dataset or you can directly code in your Kaggle notebook(Recommended since kaggle provide you gpu and good amount of Ram for processing your data. 

The above directory conatins the working code for this problem.

## What I did ?

### Steps 1: Visulized the images before and after augmentation.
#### Augmentation is a good way to improve the accuracy of your model.You can flip,mirror,zoom-in,zoom-out your images using augmentation layer.

### Step 2: Defined custom CNN model.(You can view the summary of my model in the notebook.)

### Step 3:Defined a model using MobileNet model and improved the accuracy.

If you need to further improve your accuray you can tune the hyperparameters or add some more custom layer with some base model.
A dropout layer can also be added to reduce overfitting.

You can also use any other available base model from keras library and read about them in keras documnetation.

Do not forget to change the input size for different base models.



