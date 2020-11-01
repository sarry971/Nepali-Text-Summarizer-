# Nepali-Text-Summarizer

In this project, we have implemented the idea of Extractive Text Summary for Nepali text. Extractive Text Summary is one of the type of Text Summarization technique based on the Output Type. 
The idea of Extractive Text Summarization is to give each sentence in the text a significant score and subsequently extracts the original topmost sentences concatenate them to give the summary of the text. This technique doesn't generate any new text on its own. 

Pipeline for Nepali Text Summarizer Project:

Text Preprocessing --> sentence tokenziation & word tokenization --> calculate TF*IDF score for each word in a sentence --> compute cosine similarities values between each pair of sentences using TF*IDF and compute average for each sentences --> take top M sentences based on cosine similarity avg and get their sentence index --> sort the index's sentence and put in summary 


This project mainly focuses on summarizing Nepali Text so while preprocessing 
