# MSDV ML Spring 2025 
### Final project in Machine Learning class at Parsons School of Design 2025 
<br>

## 01 
### Poli-Spec AI

##### Idea 
The main idea is to have a model that gives a text by a german politican a score. <br> 
Input: Text 
Output: 1 -> 0 = Far-right, 1 = Far-left. 
The score will be a scale on the ploitical spectrum. 
----
##### Dataset
I found this dataset https://zenodo.org/records/4542662
It has all speechs in the German Parlament from 1949 until 2017.
----
##### Preprocessing 
The data set need preproccing. I would need to extract each party name and party speaker into a new column and assign each party a score. (0 for righ and 1 for left and what in between) with their text. 
This will be a bit challenging but there is s a pattern in the text. Any speech starts with "Name (party name): speech". Using Regular Expressions will help here. 
----
##### Train Test 
The dataset will be very big. So it could be splited and evaluated. 
Maybe spliting is not very important as we can use for testing newer party speeches that are not in the dataset. 
----
### Evaluation 
Evaluation would be how accurate the model is predicting a plitical speech to be right or left. As we already know if the person speaking if a right or left leaning party leader. 
