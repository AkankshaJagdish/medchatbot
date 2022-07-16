# medchatbot
A flask based app for use in healthcare.

## Overview

This project is a  a chatbot that answers simple queries about healthcare related topics. Often, younger people do not know much about simple medicines they can take to alleviate common issues such as colds and fevers, and this project attempts to fill in this gap.

In the present situation, we are unable to provide healthcare support 24/7 in a quick and efficient manner, due to dearth of medical professionals. This chatbot will ensure that general queries of potential patients are quickly answered and they are easily directed to the correct person for their problem.

In the future, such chatbots can play an important role in getting relevant health information  to the right stakeholders at the right time. 

## Design Description

A Flask prediction API serves as backend to a HTML and JavaScript frontend. This is a retrieval based chatbot.

This chatbot uses deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. 

A special recurrent neural network (LSTM) is used to classify which category the user’s message belongs to and then the bot will give a random response from the list of responses.

The modules required are:
1.	Tensorflow
2.	Keras
3.	Natural Language processing (NLTK)
4.	Flask-Cors

## Dataset

Two specialised datasets have been merged to create a dataset for technical answers, which has then been modified to suit the current purpose. This modification creates the final dataset.

### 1st Dataset:

https://www.kaggle.com/datasets/tusharkhete/dataset-for-medicalrelated-chatbots

This has a multitude of medical issues and simple treatments for them in JSON format. 

### 2nd Dataset:

Next, for Covid-19 specific application, another JSON dataset is used. 

Link: https://contribute.geeksforgeeks.org/wp-content/uploads/WHO.txt

### Final Dataset

Modifications have been made to the dataset made by merging the first two datasets, creating the final dataset stored in the file "intents.json"


## Resulting WebApp

Initial webpage:

![image](https://user-images.githubusercontent.com/94063711/179363901-70c8a388-df4b-4dfe-834c-f0f9ab773d0f.png)

Chatbox open:

![image](https://user-images.githubusercontent.com/94063711/179363924-b2176cd1-b8ca-498d-8cf9-298687317f03.png)

Answering queries:

![image](https://user-images.githubusercontent.com/94063711/179363950-e82eac0f-60b9-44e5-8f61-d9b94bbdb195.png)

![image](https://user-images.githubusercontent.com/94063711/179363955-f22a74a2-ef0f-4785-a862-efb027edb312.png)




