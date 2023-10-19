# Automate-Emotion-Analysis
What is emotion?
Emotion a state of feeling , conscious mental reaction (such as anger or fear) subjectively experienced as strong feeling usually directed toward a specific object and typically accompanied by physiological and behavioral changes in the body

Detecting emotional state of a person by analyzing a text document written by him/her appear challenging but also essential many times due to the fact that most of the times textual expressions  are not  only direct using  emotion  words but also result  from the interpretation  of  the  meaning  of  concepts  and  interaction  of  concepts  which  are described in the text document. Recognizing the emotion of the text plays a key role in the human-computer interaction   Emotions  may be expressed by a person‟s speech, face  expression  and  written  text  known  as  speech,  facial  and  text  based  emotion respectively. 

Positive Emotion - Gratitude, Serenity, Interest, Hope, Pride, Amusement, Inspiration.
Negative Emotion- Anger, fear, resentment, frustration, and anxiety

We have used python to automate emotion from textual datasets and produced the output as a graphical plot that represents different emotions present in the textual sentences of dataset.

Solution Approach:
1.	Importing all the necessary libraries 
2.	Reading our dataset
3.	Adding emotion.txt file and  dataset file to environment
4.	Converting our dataset to lower case
5.	Cleaning the text present in dataset
6.	Removing punctuations in the process
7.	Splitting text into words
8.	Removing stop words from the tokenized words list and creating a list called final words
9.	Check if the words in final words list is also present in emotion.txt and extract the word and emotion using split
10.	Creating a new list called text_emotion and adding the word if the word is present in the emotion text file
11.	Plotting the text_emotion on the graph
12.	12.Try out the same model with a different data set and compare the results

Algorithms:
          Installing Transformers

●	Import the libraries required for building for the model
●	Create a method using the model ‘arpanghoshal/EmoRoBERTa’
●	Reading the dataset 
●	Converting the text of dataset into lowercase
●	Creating a clear set by removing punctuations
●	Splitting text to words for further processing
●	The first is an encoder that operates primarily on the input sequence 
●	The second is a decoder that operates on the target output sequence during training and predicts the next item in the sequence.
●	Apply the above created method to the dataset

Enhancement Scope:

1.	The accuracy of my model can be improved
2.	We can add emojis to my model and dataset

