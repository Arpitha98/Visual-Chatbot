# Visual-Chatbot
Title
Visual Chatbot

Github Link 
https://github.com/beril76/Visual-Chatbot

Problem Statement
To build a multi-class classifier which can classify the inputted image of an Indian monument followed by a chatbot which can answer the queries of the user regarding the classified inputted image as speech. In short, our app includes a 40 class image classifier, an interactive chatbot and a text to speech converter.

Description

Data - Images of 40 famous monuments of India Training data - 10 images for each
Validation data - 3 images for each
Images were web scraped from flickr. Text data for chatbot purpose was web scraped from wikipedia.

In our app the user can input the path of the monument image to be classified. Then the classifier built using AlexNet identifies and classifies the image.

Train accuracy - 92.23% 
Validation accuracy - 77.08%. 

Once the classification is done the user interacts with the chatbot built using AllenNLP if the user wants to know more about the classified monument. The chatbot provides the output with audio.

The app is built on Streamlit which provides the user with the options of an ABOUT page to know about HAL9000 Visual Chatbot and another option of Chatbot which includes the classifier.
