# The-Hybrid-Recommender

**Author** : Charles Gaydon

**Date** : 25/01/2018

**Context** : This work was done as part of a Machine Learning course taught at the University of Lyon, as part of the **Data Science Master's Degree**.

**Objectives** : 

We have three files, containing informations about :
- Restaurants : 461 restaurants and anonymous labels describing them, 
- Clients : 192 clients of those restaurants, i.e. that have visited at least one of them in the past, described by 9 anonymous quantitatives variables;
- Visits : a 192x461 matrix indicating whether the ith customer has visited (v(i,j) = 1) or not (v(i,j) = 0) the jth restaurant. 

We will hereby do two things :
- propose a general method to recommend or not a new restaurant to a new customer, 
- and then develop and validate an **Ensemble Chained Classifier** to recommend the top-k restaurants that could best please a new customer.

![title](pizza.png)