# Nvidia_Deep_Learning

<h1>1. MNIST Project</h1>

## The Problem: Image Classification 
<h4>In traditional programming, the programmer is able to articulate rules and conditions in their code that their program can then use to act in the correct way. This approach continues to work exceptionally well for a huge variety of problems.

Image classification, which asks a program to correctly classify an image it has never seen before into its correct class, is near impossible to solve with traditional programming techniques. How could a programmer possibly define the rules and conditions to correctly classify a huge variety of images, especially taking into account images that they have never seen?</h4>

## The Solution: Deep Learning

<h4>Deep learning excels at pattern recognition by trial and error. By training a deep neural network with sufficient data, and providing the network with feedback on its performance via training, the network can identify, though a huge amount of iteration, its own set of conditions by which it can act in the correct way.</h4>
......................................................................................................................................................................
<h1>2.  Image Classification of an American Sign Language Dataset</h1>

## American Sign Language Dataset

<h4>The [American Sign Language alphabet](http://www.asl.gs/) contains 26 letters. Two of those letters (j and z) require movement, so they are not included in the training dataset. </h4>
......................................................................................................................................................................
<h1>3. Convolutional Neural Networks</h1>
<h4>
* Prep data specifically for a CNN
* Create a more sophisticated CNN model, understanding a greater variety of model layers
* Train a CNN model and observe its performance</h4>
......................................................................................................................................................................
<h1>4. An Automated Doggy Door</h1>
<h4>Created a doggy door that only lets dogs (and not other animals) in and out. We can keep our cats inside, and other animals outside where they belong. Using the techniques covered so far, we would need a very large dataset with pictures of many dogs, as well as other animals. Luckily, there is a readily available model that has been trained on a massive dataset, including lots of animals. 

The [ImageNet challenge](https://en.wikipedia.org/wiki/ImageNet#History_of_the_ImageNet_challenge) has produced many state-of-the-art models that can be used for image classification. They are trained on millions of images, and can accurately classify images into 1000 different categories. Many of those categories are animals, including breeds of dogs and cats. This is a perfect model for doggy door.</h4>

......................................................................................................................................................................

<h1>5. Headline Generator</h1>
<h4>We've all seen text predictors in applications like the search bars, on cell phones, or in text editors that provide autocompletion of sentences. Many of the good text predictor models are trained on very large datasets, and take a lot of time and/or processing power to train. For this exercise, our predictor will be quite simple, but it will provide some simple exposure to language processing, sequence data, and one of the classic architecture elements used to train sequences, *recurrent neural networks* or *RNNs*.</h4>

......................................................................................................................................................................

<h1>6. Recognizing Rotten and Fresh Fruits</h1>
<h4>Trained a model to recognize fresh and rotten fruits. The dataset comes from [Kaggle](https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification). The dataset structure is in the `data/fruits` folder. There are 6 categories of fruits: fresh apples, fresh oranges, fresh bananas, rotten apples, rotten oranges, and rotten bananas. This  means that our model would require an output layer of 6 neurons to do the categorization successfully.We also need to compile the model with `categorical_crossentropy`, as we have more than two categories.</h4>
