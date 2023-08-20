# Decision_Trees

## Problem Statement

**Company data :**

A cloth manufacturing company is interested to know about the segment or attributes causes high sale. 

Approach - A decision tree can be built with target variable Sale (we will first convert it in categorical variable) & all other variable will be independent in the analysis.

**Fraud Check :**

Use decision trees to prepare a model on fraud data 

treating those who have taxable_income <= 30000 as "Risky" and others are "Good"


# ➳ Decision Tree Algorithm

Classification is a two-step process, learning step and prediction step, in machine learning. In the learning step, the model is developed based on given training data. In the prediction step, the model is used to predict the response for given data. Decision Tree is one of the easiest and popular classification algorithms to understand and interpret.

![tree](https://github.com/yagniksorathiya/Decision_Trees/assets/129974278/c3f399ac-a1e6-4a49-8276-e9879290875a)

Decision Tree algorithm belongs to the family of supervised learning algorithms. Unlike other supervised learning algorithms, the decision tree algorithm can be used for solving **regression and classification problems** too.

The goal of using a Decision Tree is to create a training model that can use to predict the class or value of the target variable by **learning simple decision rules** inferred from prior data(training data).

In Decision Trees, for predicting a class label for a record we start from **the root** of the tree. We compare the values of the root attribute with the record’s attribute. On the basis of comparison, we follow the branch corresponding to that value and jump to the next node.

## ↳ Types of Decision Trees

Types of decision trees are based on the type of target variable we have. It can be of two types:

+ **Categorical Variable Decision Tree:** Decision Tree which has a categorical target variable then it called a Categorical variable decision tree.

+ **Continuous Variable Decision Tree:** Decision Tree has a continuous target variable then it is called Continuous Variable Decision Tree.

## ↳ Important Terminology related to Decision Trees

1) **Root Node:** It represents the entire population or sample and this further gets divided into two or more homogeneous sets.

2) **Splitting:** It is a process of dividing a node into two or more sub-nodes.

3) **Decision Node:** When a sub-node splits into further sub-nodes, then it is called the decision node.

4) **Leaf / Terminal Node:** Nodes do not split is called Leaf or Terminal node.

5) **Pruning:** When we remove sub-nodes of a decision node, this process is called pruning. You can say the opposite process of splitting.

6) **Branch / Sub-Tree:** A subsection of the entire tree is called branch or sub-tree.

7) **Parent and Child Node:** A node, which is divided into sub-nodes is called a parent node of sub-nodes whereas sub-nodes are the child of a parent node.

![structure-of-a-decision-tree](https://github.com/yagniksorathiya/Decision_Trees/assets/129974278/2485bfde-8a42-4146-85d5-c3922e5cb50e)

Decision trees classify the examples by sorting them down the tree from the root to some leaf/terminal node, with the leaf/terminal node providing the classification of the example.

Each node in the tree acts as a test case for some attribute, and each edge descending from the node corresponds to the possible answers to the test case. This process is recursive in nature and is repeated for every subtree rooted at the new node.
