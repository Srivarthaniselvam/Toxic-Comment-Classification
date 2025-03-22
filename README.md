# Toxic-Comment-Classification
  This project focuses on building an NLP model that predicts the probability of various types of toxic comments. The model aims to improve online discussions by identifying toxic, severely toxic, obscene, threatening, insulting, and identity-hate comments.
# Overview
      Online discussions often face challenges due to abuse and harassment, discouraging participation and limiting free expression. Many platforms struggle with comment moderation, leading to community restrictions or comment shutdowns.

The Conversation AI team (a research initiative by Jigsaw and Google, part of Alphabet) has been working on AI-powered moderation tools. Their Perspective API provides toxicity detection models, but improvements are needed to reduce false positives and allow custom toxicity filtering.

This project involves building a multi-headed model to detect multiple forms of toxicity better than existing models. The dataset consists of comments from Wikipedia’s talk pages, labeled by human raters.
# Disclaimer: The dataset contains offensive and profane text as it aims to train models to detect such content.

# Types of Toxicity
Each comment is labeled with one or more of the following toxicity types:
✅ toxic – general toxic language
✅ severe_toxic – highly aggressive or offensive content
✅ obscene – profanity or vulgar expressions
✅ threat – direct threats towards individuals or groups
✅ insult – derogatory or insulting language
✅ identity_hate – hate speech targeting identities

# Tech Stack & Tools
 - Programming Language: Python
 - Libraries & Frameworks: TensorFlow, Keras, Scikit-learn, NLTK, SpaCy
 - Modeling: Deep Learning (LSTMs, BERT, Transformers)
 - Dataset: Wikipedia Talk Page Comments
 - Deployment: Flask/Django (if applicable)

# Results & Performance 
 - Fine-tuned BERT/Transformer models for improved classification
 - Potential applications in comment moderation, social media filtering, and online forums

# References & Dataset Source
 - Dataset: Wikipedia Toxic Comment Dataset (Kaggle)
 - Perspective API: Google Jigsaw Perspective
 - Research Paper: Toxic Comment Classification Using NLP & Deep Learning
