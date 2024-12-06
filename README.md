# XAI FINAL PROJECT

<img src="https://github.com/user-attachments/assets/f6aec4bd-bea7-40b5-b9ee-b3ba56e24b7c" width="200"/> 
<img src="https://github.com/user-attachments/assets/66a84e10-bffe-418e-9396-763fbc5dab87" width="200"/> 
<img src="https://github.com/user-attachments/assets/27c1d3dc-efad-44ae-8bfb-6d06111c36ca" width="200"/>



# LIME and Cross-Domain Sentiment Analysis Using BERT
## Overview
This project explores the use of LIME (Local Interpretable Model-agnostic Explanations) to evaluate the performance of a BERT model trained on one domain and applied to another domain. Specifically, it focuses on understanding how transfer learning in NLP (Natural Language Processing) works, and how LIME can provide insights into the model's predictions when applied to cross-domain data. iT also brings to light the complicated nature of neutral sentiments.

# Research Question
"How does LIME facilitate the evaluation of a BERT model's transfer learning performance?"

The goal of this project is to apply LIME to a sentiment analysis task, where a model trained on a movie review dataset is tested on a different domain — COVID-19-related tweets. By doing so, it investigates how well transfer learning applies across domains and why the model might succeed or fail.

# MY FINDINGS :
1. The fine tuned model had an accuracy score of 59.48% on the Covid tweets dataset. It had a 93.4% accuracy score when trained on the movie reviews data. 
1. Cross domain transfer learning sounds exciting. But its very important to make sure we know the credibility and source of the dataset- especially if its sentiment analysis. A biased dataset labeller may associate some neutral langugae with positivity or negativity and this is something the model ends up learning.
   
2. During cross domain experiments, its quite easy to overlook that fact that the results from one domain may not be helpful in another domain. Movie reviews are often written emotionally, casually and creatively. People can constuct strongly negative or positive comments with seemingly neutral words, for example, by using sarcasm. A sarcastic movie comment might be labelled negative because it is actually negative, but it uses relatively neutral or positive words. This data , when used for training can cause a model to learn an incorrect relationship between words and their associated sentiment. And then, if this model is applied to a more serious domain, such as online discourse around Covid, it can cause information to be misrepresented.

3. LIME is an excellent way to know whether a model is associated neutral words with positivity or negativity and this can give us a sense of the nuances of the  domain and the quality of the training dataset 

 
# EXAMPLES OF INTERESTING FINDINGS
![image](https://github.com/user-attachments/assets/06e6ac93-e536-4070-a134-965e0d20bc6f)

![image](https://github.com/user-attachments/assets/0d897d59-d6f6-4daa-8069-d6b2ce4eb66a)

![image](https://github.com/user-attachments/assets/6090ce68-5e1b-4366-8713-cd34c9b35ccd)



# Credits 
I used the help of Gen AI to train the model and also to help with applying LIME
