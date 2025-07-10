# Decision-tree-on-bank marketing

COMPANY: CODTECH IT SOLUTIONS

NAME: SREEMATHI.R

INTERN ID: CT06DH682

DOMAIN: MACHINE LEARNING

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

This project focuses on predicting customer subscription outcomes using decision trees on the Bank Marketing dataset. It applies classification techniques to uncover how client attributes influence marketing success.

Dataset: Real-world marketing data from a Portuguese bank.
Goal: Predict whether a client will subscribe to a term deposit (yes/no).
Model Used: Decision Tree Classifier (Gini index, max depth = 5).

Preprocessing:

Dropped duration column to avoid data leakage.
Encoded categorical variables using LabelEncoder.
Used 70% of data for training, 30% for testing.

Evaluation:

Accuracy: ~89.1%
Strong precision/recall for "no", weak recall for "yes" due to imbalance.
