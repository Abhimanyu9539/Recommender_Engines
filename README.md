# Recommender_Engines

This repo consists of the following recommender engines 

## 1. Rule Based Recommender Engine: 
Works on a set of predefined set of rules. </br>
It includes  the following categories:
-	Using Popularity
-	Buy again
-	Trending by region and category
-	Top Offers
-	New Launches

## 2. Market Basket Analysis

- Association Rule
- What are the products that are sold together mostly
- Uncover the association between items
- Works by looking for combinations of items that occur together frequently
- Cross Sell :  You bought this; most people bought this together
- Collection of items purchased by customer is item set
- Probability that a customer will purchase two items together is a confidence of the rule
- Apriori Rule : This rule provides the basic framework for the Market Basket Analysis


## 3. Content Based Recommender Engine:
- Based on items description and users preferences
- Simply put, it recommends things based on users previous choice or their enjoyment
- Based on information retrieval and information filtering

## 4. Collaborative Filtering
- Depends on gathering large amount of data and analysing it based on users interactions , reviews and purchases.
- Also depends upon their resemblance to other users
- Advantage of not relying on machine analysable content which enables it to recommend products or movies without requiring the knowledge of the products
- Based on item similarity
- Not the same basket analysis: It can span for years

User – User Collaborative System:
- Recommending user based on their purchase and similarity of their purchase to the other user

Item – Item Collaborative System:
- System computes the similarity  based on the items and not on the users


## 5. Hybrid Recommendation System

- Ensemble or combo of two other system
- Collaborative Filtering  + Content Based Filtering
- CF needs users interaction and to avoid cold start
- Is more effective
- Eg : Netflix 
- Compares users behavior such as searching content and viewing as well as by suggesting films that share qualities similar to the user rated highly


