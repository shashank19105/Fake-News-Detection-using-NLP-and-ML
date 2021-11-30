# Fake-News-Detection-using-NLP-and-ML
Project made as a part of CSE343: Machine Learning course.

## Contributors

Bharat Soni (bharat19461@iiitd.ac.in)
Jatin Yadav (jatin19270@iiitd.ac.in)
Shashank Chaurasia (shashank19105@iiitd.ac.in)
Satya Shambhavi Abhiroop Mareedu (satya19204@iiitd.ac.in)


## Abstract

Today Fake News has become a major problem wreaking havoc all over the world. True Information is crucial to Human life for important decision making. We form ideas about people or situations through access to Information. Due to Internet misinformation such as fake news, hoaxes, and violent opinions are widespread. Targeted delivery of content has put people in misinformation bubbles which are used to further one's agenda.This relates to politics, health and hate speech. This can impact us financially, health-wise, democratically and socially.Hence, we plan to propose a solution for fake news detection which incorporates sentiment as an important feature to improve accuracy.



## Introduction


We propose Binary Classification models that we can use to classify if a statement is reliable or unreliable. This classification process has diverse practical applications as it automates the assignment of statements to either reliable or not with a very high accuracy. We classify based on the title, author, text, verbs etc.




## Description of the repository and Conclusion

There are 2 data sets across which we have implemented our models. Promising results were achieved on both the datasets. We have 2 different python notebooks for both the datasets. The reason for performing on two datasets was to compare the training of models based on (Author + Title) vs (Title + Body) of news articles. Similar results were achieved on both. However it was concluded that (Author + Title) gave better accuracy for less computational time. Hence it can be concluded that fake articles arise from clickbait titles and same authors are more likely to spread fake news. The content of a new article is not as useful as the other two when training binary classification.
