# HealthCare Data processing and Predicting treatment for a disease

## Table of Contents
‘BeHealthy’ is a health tech company which aims to connect the medical communities with millions of patients across the country. 

The company has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

 
Let’s take a look at the following snippet of medical data that may be generated when a doctor is writing notes to his/her patient or as a review of a therapy that he or she has done.


“The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”


As you can see in this text, a person with a non-medical background cannot understand the various medical terms. We have taken a simple sentence from a medical data set to understand the problem and where you can understand the terms ‘cancer’ and ‘chemotherapy’. 

Suppose you have been given such a data set in which a lot of text is written related to the medical domain. In the dataset which will be provided, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, which you saw in the aforementioned example that the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence.


But, note that it is not explicitly mentioned in the dataset about the diseases and their treatment.

So the challenge is to build an algorithm to map the diseases and their respective treatment. 
Next time, when we feed the disease to the algorithm, it should be able to predict the treatment.


* [Technologies Used]
Python, Jupyter, en_core_web_sm from Spacy library

## Steps involved
1) Data preprocessing
2) Tokenisation
3) Concept Identification using POS tagging
4) Defining features for Conditional Random Fields
5) Build the CRF Model using crfsuite from sklearn
6) Identifying Diseases and Treatments using Custom NER

## Contact
Created by [@RakshiGit] - feel free to contact me!
