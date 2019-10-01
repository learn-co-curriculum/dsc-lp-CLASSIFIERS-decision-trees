---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 5 Sec 34 V2         <br/>
**Topic**: Decision Trees <br/>
**Amount of time**: 60 minutes <br/>
**Author**: Alison Peebles


***

#### Lesson Summary:

This lesson begins with several entertaining examples regarding how humans might make decisions based on varying criteria. These fun examples are then leveraged into a more formal example of decision trees before further investigating the threshold criteria for branches. 

#### Topic:

Decision Trees

#### Learning goals for this lesson:

* Students will be able to procedurally describe a decsision tree
* Students will be able to explain information gain
* Students will be able to implement a decision tree classifier with scikit-learn
* Students will be able to explain entropy
* Students will be able to explain a Gini impurity

#### Prerequisite knowledge:

* Students should be adept at using Pandas DataFrames
* Students should have previous exposure to classifiers and their evaluation

#### Prequisite Learn-Materials:

* [Introduction to Supervised Learning](https://github.com/learn-co-curriculum/dsc-intro-to-supervised-learning)
* [Introduction to PAC Learning Theory](https://github.com/learn-co-curriculum/dsc-introduction-to-pac-learning-theory)
* [Introduction to Decision Trees](https://github.com/learn-co-curriculum/dsc-introduction-to-decision-trees)
* [Entropy and Information Gain](https://github.com/learn-co-curriculum/dsc-entropy-and-information-gain)

#### Post Learn-Materials:

* [ID3 Classification Trees: Perfect Split with Information Gain - Lab](https://github.com/learn-co-curriculum/dsc-ID3-trees-lab)
* [Building Trees using scikit-learn](https://github.com/learn-co-curriculum/dsc-decision-trees-with-sklearn-codealong)
* [Building Trees using scikit-learn - Lab](https://github.com/learn-co-curriculum/dsc-decision-trees-lab)
* [Hyperparameter Tuning and Pruning in Decision Trees](https://github.com/learn-co-curriculum/dsc-tuning-decision-trees)
* [Hyperparameter Tuning and Pruning in Decision Trees - Lab](https://github.com/learn-co-curriculum/dsc-tuning-decision-trees-lab)

#### Advanced Extensions:
* [Regression with CART Trees](https://github.com/learn-co-curriculum/dsc-regression-cart-trees-codealong)
* [Regression with CART Trees - Lab](https://github.com/learn-co-curriculum/dsc-regression-cart-trees-lab)
* [Regression Trees and Model Optimization - Lab](https://github.com/learn-co-curriculum/dsc-tuning-regression-trees-lab)

#### Relevant learning goals from Airtable: 

DECISION_TREES.1.rec56j5h6xwuWL36n
DECISION_TREES.1.rec8b2VHVn3Si9U1g
DECISION_TREES.1.rec9gQg1rrgUEktox
DECISION_TREES.1.rec9qrRVKoMJ20PZS
DECISION_TREES.1.recJI3yn1vIBTCpb2
DECISION_TREES.1.recJVysBIpKC6oNhD
DECISION_TREES.1.recSSzlbfeyjBN3ZO
DECISION_TREES.1.recZVmj5O6fBsLScI
DECISION_TREES.1.recahkP9LxhKB9mwC
DECISION_TREES.1.recdetQl5gPtzPL2G
DECISION_TREES.1.recs3fSlZgw9TH0ia
DECISION_TREES.2.rec1ohGTf7vxUZaQF
DECISION_TREES.2.rec4G3v7kcfSm3EiP
DECISION_TREES.2.rec5lkRTlMo1C6FZS
DECISION_TREES.2.recRpGrZhcpCjF3Ff
DECISION_TREES.2.recUTIcUmjw0Yfnaa
DECISION_TREES.2.recYKdqB1uJFD8UhQ
DECISION_TREES.3.recKDWYWdTSQxBu6Z
DECISION_TREES.3.recM87U3e2pD6c96h
DECISION_TREES.3.recTbHkbfu3M55uH2
DECISION_TREES.3.reccJKQS37ofoF9nP
DECISION_TREES.4.rece92lWFUajExNkK

#### Materials

* Ipython notebook

#### Vocab / Concepts 

* Decision Trees
* Nodes
* Information Gain
* Entropy
* Gini impurity

#### Lesson Outline:

* Real World Decision Criteria (8 minutes)
* Examining a Decision Tree Chart (10 minutes)
* Choosing Best Features: Splitting a Dataset by Hand (10 minutes)
	* **Check for student understanding**:
		Q: Which feature is more accurate in predicting whether and individual pays their bill
		A: Salary. Explanation: observations divided along this feature better align with the dependent variable we are trying to model.
* Entropy and Information Gain (5 minutes)
	
* Gini Impurity (5 minutes)
	* **Check for student understanding**:
		Q: Exercise: Calculate the Gini Impurity for our toy dataset above.
* Building a Decision Tree with Python and scikit-learn (10 minutes)
	* **Check for student understanding**:
		Q: How does this decision tree predict whether an individual will pay their bill? How accurate is it?
		A: See the interpretation notes in the teacher guide
* Pros and Cons of Decision Trees (5 minutes)
* Summary (5 minutes)
	* **Check for student understanding**:
		Q: Explain what a decision tree is and how to implement one using scikit-learn.