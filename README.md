# fake-real-news-detector

<p>Here is the link to my project : https://nipun00-fake-real-news-detector-project-9ojykr.streamlitapp.com

# Fake News Detection
Fake news is one of the biggest problems because it leads to a lot of misinformation in a particular region. Most of the time, spreading false news about a community’s political and religious beliefs can lead to riots and violence as you must have seen in the country where you live. So, to detect fake news, we can find relationships between the fake news headlines so that we can train a machine learning model that can tell us whether a particular piece of information is fake or real by simply observing the headline in the news. So in the section below, I’m going to introduce you to a machine learning project on fake news detection using the Python programming language.
##DATASET
The dataset I am using here for the fake news detection task has data about the news title, news content, and a column known as label that shows whether the news is fake or real. So we can use this dataset to find relationships between fake and real news headlines to understand what type of headlines are in most fake news.<br />
Dataset link : https://www.kaggle.com/datasets/hassanamin/textdb3?resource=download <br />
This dataset is very large and luckily it still has no missing values, we need to train a machine learning model and the label column as the values we want to predict.
Now After separating the dataset into training and testing sets, and then I’ll use the Multinomial Naive Bayes algorithm to train the fake news detection model.<br />
![image](https://user-images.githubusercontent.com/112875065/190887823-764829d1-27bb-4330-b2e8-5a0415cbf1bb.png)<br />
![image](https://user-images.githubusercontent.com/112875065/190887829-84bbe79b-7ee2-4bd3-a4a7-fc304814f333.png)<br />
As, We can see the accuracy score, so we can conclude it won't predict correct every time.
Now let’s test this model. To test our trained model, I’ll first write down the title of any news item found on google news to see if our model predicts that the news is real or not:<br />
![image](https://user-images.githubusercontent.com/112875065/190887873-b457b898-2d2b-493c-a83e-0e56becc92cf.png)<br />
![image](https://user-images.githubusercontent.com/112875065/190887879-6fe585c1-da93-49d2-a84f-b56568b79713.png)<br />
Now I’m going to write a random fake news headline to see if the model predicts the news is fake or not:<br />
![image](https://user-images.githubusercontent.com/112875065/190887889-267cd371-b7d8-4728-845b-6ec8b368fc23.png)<br />
![image](https://user-images.githubusercontent.com/112875065/190887896-14bc09e3-2475-47d3-825a-a7c109cfcbdd.png)<br />

# SUMMARY 
So this is how we can train a machine learning model for the task of fake news detection by using the Python programming language. Fake news is one of the biggest problems because it leads to a lot of misinformation in a particular region. I hope you liked this project on the task of Fake News detection with machine learning using Python.
