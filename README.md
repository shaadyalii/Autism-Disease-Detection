# Autism-Disease-Detection
Autism Disease Detection Project using Support Vector Machine (SVM) for Artificial Intelligence (2) [CS413P] at Faculty of Computers &amp; Information Sciences, Mansoura University


# Table of Content

* [Brief](#Brief)
* [DataSet](#DataSet)
* [How It Works](#How_It_Works)
* [Tools](#Tools)
* [Remarks](#Remarks)
* [Usage](#Usage)



# Brief

Autism Spectrum Disorder (ASD) is a developmental condition characterized by challenges in social skills, repetitive behaviors, and both verbal and nonverbal communication. It is influenced by a combination of genetic and environmental factors, with each individual displaying a unique set of strengths and challenges. The way individuals with autism learn, think, and problem-solve can vary widely, from highly skilled to severely challenged.

Research shows that high-quality early intervention can greatly improve communication, social skills, and brain development. However, the diagnostic process can often take years, delaying access to critical support and therapies. Early and accurate screening is essential to ensure timely intervention and better outcomes for individuals with ASD.


# DataSet

The dataset used in this project is the [Autism-Screening Data Set](https://www.kaggle.com/datasets/andrewmvd/autism-screening-on-adults) from Kaggle.  is designed to identify individuals who are likely to have Autism Spectrum Disorder (ASD). This dataset consists of a combination of demographic details, behavioral assessments, and family medical history, all of which can help predict ASD tendencies


# How_It_Works

 • The dataset is loaded from a CSV file (Autism.data).
 
 • We convert the "age" column to numeric values and replace any erroneous strings.
 
 • The dataset is split into features (X) and target labels (Y).

 • Categorical columns (e.g., gender, ethnicity) are encoded using LabelEncoder to convert them into numeric values.
 
 • Standard scaling is applied to the features.
 
 • The SVM model is trained on the training data.
 
 • Predictions are made based on the user input.

 

# Tools

  I.	VScode(IDE)
  
  II.	Python 3.x
  
  III. numpy
  
  IV. pandas 

  v. matplotlib
  
  VI. scikit-learn
  



# Remarks

* This Python program was run and tested in VScode.
  
* Ensure the required libraries are installed by running:
  
  ```bash
  pip install numpy pandas scikit-learn  matplotlib 
# Usage

To begin utilizing this application, follow these steps:

1. Clone this repository:
   
   ```bash
   git clone https://github.com/shaadyalii/Autism-Disease-Detection

2. Navigate to the cloned repository:

   ```bash
   cd Autism-Disease-Detection

3. Run the Script:

   ```bash
   astumm.py
