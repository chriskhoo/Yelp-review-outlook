Dynamic default ratings
===============
An academic exercise looking at the reviews and ratings from the Yelp Dataset.

Author: Christopher Khoo

Project: Springboard Capstone Project 1

## Contents of Read Me
1. Project Proposal

Atom preview: `ctrl + shift + m`

--------------
# Project Proposal

## Contents of proposal
1. Context
2. Goal
3. Data & Sources
4. Approach
5. Tech stack
6. Deliverables
7. Personal learning objectives

## 1. Context (What)
With the event of social media and online directories - such as Yelp, TripAdvisor and Zomato - online marketing is becoming an increasing important aspect of promoting a business.

In particular, reviews and ratings of a restaurant could make or break a new establishment. It is now a common practice for customers to checkout a restaurant (or establishment) using online reviews and ratings before giving it a try.

This project proposes predicting the rating based on the review written.



## 2. Goal (Why)
The prediction could be used as part of a new feature to change the default rating from a static value (e.g. default of 3 stars or 0 stars) into a dynamic default value based on the review. This default rating would still need to be accepted by the reviewer.

Alternatively, this could be used to trigger is a verification for the user to confirm the rating if the predicted rating is significantly different from the actual rating.  

An easier review experience with more reflective ratings, would add value to all the major stakeholders:
- a dynamic rating could help reduce the cognitive load on the reviewers, making reviews easier
- better rating accuracy helps new customers with their online research
- more reflective ratings  reduce frustration / confusion of establishment proprietors arising from an unconsidered rating
- the platform's (e.g. Yelp) quality of reviews is improved - providing better, cleaner data

## 3. Data & Sources
The dataset was obtained as part the '[Yelp dataSet Challenge - Round 10](https://www.yelp.com.sg/dataset)' (September 1, 2017 to December 31, 2017)

In particular, the `review.json` file from the JSON dataset.

Note that in line with the terms and conditions, the raw dataset will not be posted in this repo.

## 4. Approach
This exercise explore a range of NLP techniques.

#### Bag of words
Pre-processing the data:
- Case conversion
- Punctuation removal
- (REGEX expressions) ?
- Removal of stop words
- Stemming / Lemmatization

Training predictive models
- Logistic regression
- Random forest
- CART

Validation techniques
- K-folds Validation

Additional processing
- Sub-topic extraction:
https://www.yelp.com.sg/html/pdf/YelpDatasetChallengeWinner_ImprovingRestaurants.pdf
- Clustering by: Hierarchical clustering, K-means clustering

Visualisation techniques
- Clustered word clouds: https://www.yelp.com.sg/html/pdf/YelpDatasetChallengeWinner_WordCloud.pdf
- Trees?

## 5. Tech & packages
Language: Python
Packages: TBD

## 6. Deliverables
- code (GIT)
- Slide deck
- Blog post

## 7. Personal learning objectives
- Explore methods used in an NLP problem
- Explore visualisation of the findings
- Begin documentation of the findings using a blog

------
