# Capstone Proposal

## Dog Breed Classifier

### Overview
As part of Udacity's Machine Learning Nanodegree course, as a final project, chosen dog breed classifier problem which is well known
in the machine learning community and can be found on [Kaggle](https://www.kaggle.com/c/dog-breed-identification/overview/description)

### Overview
The aim of this project is to write an algorithm that could be used as part of a web application which is able to accept an image as input. 
If a dog is detected in the image, it will provide an estimate of the dog's breed.  If a human is detected, it will provide an estimate of the dog breed that is most resembling.
The image below displays potential sample output of this project. 

![Sample Output](sample_dog_output.png)
 
 ### Datasets and input
 In this solution, the datasets are images of dogs and humans provided by Udacity.
 
 [Dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
 
 [Human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)
   
 ### Solution Statement
I will use Convolutional Neural Networks (CNN) to implement an algorithm which is an ideal for analysing images and predict the dog breed. The CNN is a deep learning algorithm
using transfer learning which takes image as input, analyse it and produce the result. 
 
 ### Benchmark Model
  As per the project goal,
 the solution should identify at least 6 out of 10 images (60%), however, I will try to do it 70% accuracy and will measure this percentage by using the test dataset.
 
 ### Evaluation Metrics
 Since out data is an unbalanced, simple accuracy calculation may not be sufficient. I will use the multi class log loss metrics to evaluate models.  
 
 ### Project Design
 To produce the solution, I will be using the Convolutional Neural Networks (CNN) steps given in the notebook provided by Udacity nanodegree engineer program as follows:
  
  * Step 0: Import Datasets
  * Step 1: Detect Humans
  * Step 2: Detect Dogs
  * Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
  * Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
  * Step 5: Write your Algorithm
  * Step 6: Test Your Algorithm

### References

[Kaggle dog breed identification](https://www.kaggle.com/c/dog-breed-identification/overview/description)

[Convolutional neural network](https://en.wikipedia.org/wiki/Convolutional_neural_network)
 
 
 





