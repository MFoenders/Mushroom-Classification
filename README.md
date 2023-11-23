# 🍄 Mushroom Classification Competition

## 🌲 Introduction
In Catalonia, the autumn season brings an exciting mushroom hunting competition. However, recent years have seen a concerning trend: the accidental picking of poisonous mushrooms, mistaken for edible ones. This has put a strain on the healthcare system. The Department of Health has commissioned the development of a model that can differentiate between poisonous and edible mushrooms based on basic image attributes, emphasizing the identification of features indicative of poisonous mushrooms.

## 🚑 Problem Statement
The challenge for mushroom pickers is distinguishing safe mushrooms from dangerous ones. Our dataset consists of 8000 mushrooms, characterized as follows:
- 🟢 112 are edible but not commonly consumed.
- 🔴 0 are poisonous and have been ingested.

Our objective is to classify these mushrooms accurately to promote safety and enjoyment during the competition.

## 📊 Dataset Features
We're working with a dataset that includes six categorical features, providing essential insights into each mushroom's characteristics:
1. **Cap Shape**
2. **Cap Color**
3. **Bruises**
4. **Stalk Color Above Ring**
5. **Stalk Color Below Ring**
6. **Population**

## 🤖 Model Development
To tackle this classification task, we utilized the Random Forest model for its efficacy in handling categorical data and its robustness against overfitting. We initially compared its performance with the K-Nearest Neighbors (KNeighborsClassifier) model. After establishing the superiority of the Random Forest model in our context, we further refined our approach by employing ROC curves and AUC scores. This allowed us to determine the optimal threshold for classification, ensuring the highest accuracy in distinguishing between poisonous and edible mushrooms.
