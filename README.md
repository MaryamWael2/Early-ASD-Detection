# Early-Stage Detection of Autism Spectrum Disorders

The objective of this project was to address 10 key questions about the dataset using data analysis techniques. Additionally, three machine learning models were developed to predict whether a child has exhibited symptoms of Autism Spectrum Disorder (ASD).

## Project Overview

Autism spectrum disorder (ASD) is a developmental disability caused by differences in the brain. People with ASD may behave, communicate, interact, and learn in ways that are different from most other people. ASD can sometimes be detected at 18 months or younger. By age 2, a diagnosis by an experienced professional can be considered very reliable [1]. Early diagnosis is important because it allows young children with autism to be taught the skills needed to enhance their quality of life in a playful and systematic way. If left undiagnosed, the individual might face difficulty interacting with their community [2]. 

## Datasets

The dataset used in this project [3] consists of 19 columns and 1054 rows. 
The columns are: (A1 – A10, Age_Mons, Qchat-10-Score, Sex, Ethnicity, Jaundice, Family_mem_with_ASD, who completed the test, Class/ASD Traits). 
Columns A1 to A10 are answers to 10 yes or no questions asked to the child’s care provider. The answers to these questions determine whether the child has ASD traits or not. 
Qchat-10-Score is a score ranging from 1 to 10 that counts the number of “yes” answers to the A1 to A10 questions. The questions are listed below:
1. Does your child look at you when you call his/her name?
2. How easy is it for you to get eye contact with your child?
3. Does your child point to indicate that s/he wants something?
4. Does your child point to share interest with you?
5. Does your child pretend?
6. If you or someone else in the family speaks, does your child follow where you’re looking?
7. If upset, does your child show signs of wanting to be comforted?
8. Would you describe your child’s first words as:
9. Does your child use simple gestures?
10. Does your child stare at nothing with no apparent purpose?

## Models 

Three machine learning models were used in this project:
- **Random Forest**
- **SVM**
- **Logistic Regression**

## Model Performance

The model's performance is evaluated based on its ability to accurately predict whether or not the child has ASD symptoms. The following metrics are used to assess the models:
- **Accuracy Score**
- **Confusion matrix**
- **F1 Score**

## Refernces
[1] Dillenburger, K. (2014, October 28). Why early diagnosis of autism in children is a good thing. The Conversation. https://theconversation.com/why-early-diagnosis-of-autism-in-children-is-a-good-thing-33290 

[2] Signs & Symptoms | Autism Spectrum Disorder (ASD) | NCBDDD | CDC. (2021, March 29). Centers for Disease Control and Prevention. https://www.cdc.gov/ncbddd/autism/signs.html 

[3] K. Vakadkar, D. Purkayastha, and D. Krishnan, “Detection of autism spectrum disorder in children using machine learning techniques,” SN Computer Science, vol. 2, no. 5, Jul. 2021, doi: 10.1007/s42979-021-00776-5.
