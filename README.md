# Project-Lion

## Problem Statement and Background
Being funny is far too difficult, so why not let a system with no understanding of humor generate jokes for you? The goal of our project is to explore the concept of humor through joke generation via deep neural networks. This model will generate a joke based on an input context. In addition to constructing a humor generating neural net, we plan on analyzing the resulting network to try and understand the semantic features that go into the construction of the jokes.

## Team
### Shun Lin
4th year EECS student.

### Jerry Chen
4th year CS student.

### Allen Chen
4th year CS and Statistics student. 

### Sakshi Madan
4th year EECS student.

## Data Source
The data will be provided to us through Kaggle. We do not need to access any API to fetch the data in real time. We just have to download the data to our local/remote machine or use Kaggle's online kernel to fetch data stored on Kaggle. There are 231,657 records that were originally scraped from reddit, stupidstuff.org and wocka.com. We will also be filtering out offensive jokes in the data, such as jokes that contain inappropriate words, but there will be enough data for us to train, validate, and test our models.

[A dataset of English plaintext jokes](https://github.com/taivop/joke-dataset)

[Short Jokes Dataset from Kaggle](https://www.kaggle.com/abhinavmoudgil95/short-jokes)

[Anonymous Ratings from the Jester Online Joke Recommender System](http://eigentaste.berkeley.edu/dataset/)

## Evaluation

We evaluate our model by monitoring the loss on our RNN model that we are going to build. We want the loss on the machine generated jokes to be as low as possible on both the validation and test dataset. The ultimate evaluation of our joke generating system is to make people laugh, and not about the score on the RNN model. We can accomplish this evaluation by sending out surveys to real people, asking whether the jokes presented were funny and evaluating the model based on the feedbacks. We will also make sure the jokes are original and do not already exist from the dataset that we trained the network on.
