# Project Description
With the objective of optimizing the accuracy of binary classification of reviews (good or bad), different deep learning models are employed in the project. 
In all of them, DistilBERT is used as a base pre-trained model and different techniques are used on top of that. 
These are data augmentation using Synonym Augmenter, Zero-Shot Learning and Data Generation with LLM using ChatGPT 2 prompt. 
We also explore the learning curve of the model by training it on different % of the trainning dataset. Finally, we also perform Model Knowledge Distillation using tiny-Bert as a base pre-trained model for our student model.

# Data
amazon_polarity dataset from Huggingface https://huggingface.co/datasets/amazon_polarity

# Results
See Executive Summary and Results document
