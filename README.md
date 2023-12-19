# Music recommender system

A **recommender** (or recommendation) **system** (or engine) is a filtering system which aim is to predict a rating or preference a user would give to an item, eg. a film, a product, a song, etc.
  
There are two main types of recommender systems:

- Content-based filters: [Medium post](https://medium.com/@meinzaugarat/the-abc-of-building-a-music-recommender-system-part-i-230e99da9cad)
- Collaborative filters: [Medium post](https://medium.com/@meinzaugarat/the-abc-of-building-a-music-recommender-system-part-ii-65ec3900d19f)

> *Content-based methods* gives recommendations based on the similarity of two song contents or attributes while 
> *collaborative methods* make a prediction on posible preferences using a matrix with ratings on different songs.

**Content-based methods** are computationally fast and interpretable. However, they have a severe disability of only suggesting content that is very similar to the source, sometimes causing reptition. This recommendation method looks for simple features and ties in the content together when they have enough similarities. This can cause recommending highly similar content, at which point they are practically identical. 

**Collaborative-based methods** work with an interaction matrix, also called rating matrix. The aim of this algorithm is to learn a function that can predict if a user will benefit from an item - meaning the user will likely buy, listen to, watch this item. Since this is a prediction based recommendation system, the accuracy is lower than the content-based method. However, it does provide new perspectives and doesn't provide identical content like its counterpart.

Among collaborative-based systems, we can encounter two types: **user-item** filtering and **item-item** filtering. 

#

The aim of this project is to:

Build a collaborative filtering music recommeder system using the Million Song Dataset; a freely-available collection of audio features and metadata for a million contemporary popular music tracks.
