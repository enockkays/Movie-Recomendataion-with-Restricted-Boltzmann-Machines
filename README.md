# Movie-Recomendataion-with-Restricted-Boltzmann-Machines in PyTorch

![image](https://user-images.githubusercontent.com/32764779/161734502-0b68322c-8277-4157-a86c-bd237812c3dd.png)

## Dataset
We are using the MovieLens 1M Dataset. This set contains 1 million ratings of approximately 4000 movies made by approximately 6000 users. The model will be trained on this dataset and will learn to make predictions whether a user would like a random movie or not. GroupLens Research has collected and made available rating data sets from the MovieLens web site (http://movielens.org).

## Model Architecture
Restricted Boltzmann Machines (RBMs) are neural networks that belong to so called Energy Based Models. A practical implementation of a Restricted Boltzmann Machine which serves as a Recommender System and can predict whether a user would like a movie or not based on the users taste. As it can be seen in the Figure below, a RBM consists out of one input/visible layer (v1,…,v6), one hidden layer (h1, h2) and corresponding biases vectors Bias a and Bias b. The absence of an output layer is apparent. But as it can be seen later an output layer wont be needed since the predictions are made differently as in regular feedforward neural networks.
The model is implemented in an object oriented manner. The Restricted Boltzmann Machine is a class with all necessary operations like training, loss, accuracy, inference etc. 

![image](https://user-images.githubusercontent.com/32764779/161732590-19b9ead6-b324-4fa4-8ab9-07ba99b07bb9.png)

## Training
The training of the Restricted Boltzmann Machine differs from the training of a regular neural networks via stochastic gradient descent. 

## Performance of the Model
![image](https://user-images.githubusercontent.com/32764779/161776301-51d3e209-ee38-4343-b050-d2eb21b25c5b.png)
