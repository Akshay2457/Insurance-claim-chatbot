# Insurance-claim-chatbot
chatbot for insurance claim process  

#Problem statement:
An insurance claim is a formal request by a policyholder to an insurance company for coverage or compensation for an overed loss or policy event. In our project we are creating chatbot that allows to connect with customers in a personal without the expense of human representatives

#Dataset:
we have created a duplicate data which has Final bill, discharge summary, medical certificate, prescription, and blood reports. All of our data sets are upload in folder.

#Methodolgy:
In this prject we are creating three servers they are Rasa server, Rasa actions server, Flask server.

Input(images) -image processing (text extraction from images,using tesseract and pytesseract)and stores in rasa.
Rasa chatbot server and action server
We wrote stories, intents, actions in rasa
These be the interaction to customer or user.
This is backend
Flask server
Here we connected rasa to the flask.
In flask server we first upload the image files in it and the image files are text extracted and store xtracted data in rasa backend.
Chatbot appears in it interaction starts with the user we ask the details like what case?, what is the situation of the patient?, do patient have any health issues?
By taking information from the user we predict that patient may or may not claim his insurance policy and inform him with chat.
The chat will end when the user gives bye and close the chat.
#requirments:
We are using packages like json, cv2, pytesseract, sys, os, re, datetime, joblib, random, flask, and rasa
