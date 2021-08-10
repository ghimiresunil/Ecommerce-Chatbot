## Introduction

![](https://graspcoding.com/wp-content/uploads/2020/08/Chatbot-AI-project.png)

In this project, we’ll build a retrieval based chatbot. As we all know, chatbot usually works as an assistant to the customer. And the main purpose of the chatbot is to assist business terms in their consumer interaction by providing accuracy, customization,  reliability, and scalability. Thus, while building a chatbot we are using Keras which is a Deep Learning Library, Natural Language Processing Toolkit (NLTK), Tkinter, and some other helpful libraries. 

## Steps involved to know how retrieval based chatbot work

- Based on the conveyed or entered input, the retrieval-based chatbot return the response to the customer.
- Perform a task called “customer request analysis” in which model the data or knowledge provided by the customer and reinforce the meaning or logic behind it.
- Later, collect and return the performance with a specific answer when they recognize the intent.

## Project File Structure

- train_chatbot.ipynb: This notebook file is used to recognize what the customer wants the bot to do.
- intents.json: This intents.json file contains patterns and responses based on the tags. And, also used to train the model.
- classes.pkl: The classes.pkl store all the tag names. So, when predicting the new message this file is used to classify the new message based on the stored tag names.

- words.pkl: The words.pkl file stores all the specific and unique words which are our model’s vocabulary.
- chatbot_model.h5: The file chatbot_model.h5 is used to store all architecture and weights of our trained model. In simple terms, chatbot_model.h5 is used to store all hierarchical data format of our trained model.
- chatbot_model.h5: The file chatbot_model.h5 is used to store all architecture and weights of our trained model. In simple terms, chatbot_model.h5 is used to store all hierarchical data format of our trained model.

## Steps involved to build your own chatbot:

- At first, Import libraries and load the data
- Pre-processing the data
- Creating training and testing data
- Creating GUI to interact with the chatbot
- Finally, Enjoy the chatbot

## Final result

https://user-images.githubusercontent.com/40186859/128869013-14e8420f-27cc-4351-9291-2649205d4c3b.mp4

<h3> Feel free to play with Tkinter and Turtle . If you have a crazy idea, then pull request 😊 </h3>
