# Plant-Disease-Detector-App

# Motivation
In India about 70% of the populace relies on agriculture. Identification of the 
plant diseases is important in order to prevent the losses within the yield. It's 
terribly troublesome to observe the plant diseases manually. It needs tremendous 
quantity of labour, expertise within the plant diseases, and conjointly need the 
excessive time interval. Hence, image processing and machine learning models 
can be employed for the detection of plant diseases.

In this project, we have described the technique for the detection of plant diseases 
with the help of their leaf’s pictures.

# Dataset
We have used public dataset for plant leaf disease detection called 
Plant Village.The dataset consists of 87000 RGB images of healthy and unhealthy 
plant leaves having 38 classes.
The images cover 14 species of crops, including: apple, blueberry, cherry, grape, 
orange, peach, pepper, potato, raspberry, soy, squash, strawberry and tomato. It 
contains images of 17 basic diseases, 4 bacterial diseases, 2 diseases caused by 
mold (oomycete), 2 viral diseases and 1 disease caused by a mite. 12 crop species 
also have healthy leaf images that are not visibly affected by disease.

# Algorithm for Training of Model
• Load the dataset.

• Divide dataset into training and validation datasets.

• Perform data pre-processing steps

• Convert the range of pixels from [0-255] pixels to [0-1] pixels.

• Do augmentation i.e., generate more image using rescaling, rotation function to increase the efficiency of model.
• Train model with inception layer which is predefined model with 48 layers.

• Apply more layer with Sequential function.

• Now compile the model with loss function and optimizers (MLP).

• Fit the train dataset into the model.

# ALGORITHM FOR TESTING
• Scan the image of leaf.

• Resize the size to 224X224.

• Convert the range of pixels from [0-255] to [0-1].

• Pass the image to model we created.

• We get the output predicting which class leaf belongs to with confidence 
value.

# Layout Of Android App
![image](https://user-images.githubusercontent.com/91787844/186560788-35267e4c-2cf0-4781-a8eb-901d94d42da7.png)

![image](https://user-images.githubusercontent.com/91787844/186560880-2ba811b4-506a-4860-855c-3046c10c211c.png)

