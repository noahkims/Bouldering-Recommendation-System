# Bouldering-Recommendation-System

Joshua Tree National Park is a popular bouldering and sport climbing spot in Southern California, but finding routes to climb on your first trip or even consequent trips may be difficult without an experienced guide. 

Mountain project is a great database of routes supported by the community, and while it provides filters such as popularity and grade level, it may be hard to choose which ones you'd want to climb.

This recommendation system is aimed to provide a solution, recommending routes based on ones you've done before!

## The Model

Using data from 1000 bouldering routes from Joshua Tree National Park, the system parses through descriptions and provides recommendations based on the similarity of descriptions. 

In this model, we focus on using cosine similarity to compare texts, but also use two different methods to prepare our data for the model. 

#### Bag of Words

 Bag of words is a method that turns the texts into a collection of words, counting how many times they've appeared in the document. 

#### TF-IDF
Term Frequency - Inverse Document Frequency does something similar, but also assigns a weight based on how frequently it shows up in the document, putting less emphasis on repeated words.
