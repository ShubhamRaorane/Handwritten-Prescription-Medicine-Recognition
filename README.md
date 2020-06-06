# Handwritten-Prescription-Medicine-Recognition   [![GitHub license](https://img.shields.io/github/license/ShubhamRaorane/Handwritten-Prescription-Medicine-Recognition)](https://github.com/ShubhamRaorane/Handwritten-Prescription-Medicine-Recognition/blob/master/LICENSE)
Classifying handwritten names of medicines prescribed by doctor's.


## Description
The handwriting of doctors on prescriptions is often unintelligible.This causes people to make mistakes while reading the names of medicines and take the wrong medicines.The goal of this project was to create a prototype that can classify the snippet of the the unintelligble handwritten medicine name passed on to it from a prescription.The model which has been trained on images of handwritten snips of medicines from the doctor will classify the inputs snips of medicine images into the correct medicine name string.


## Scope of the project

This is a beginner level project intended to give a practical insight into machine learning. The project was completed within a month so It isn't a proper application.It's just a working prototype that does one task well - classification.However the the model is able to successfully predict the medicine snip in an actual doctor's handwriting with high accuracy.As data of doctors handwriting wasn't freely available and it wasn't feasible to ask doctor's for such data for such a samll project.So we decided to make our own dataset.
The approach we adopted was as follows:-
<br><br>
<b>1. First we sought out prescriptions from our own homes that we had that had mildly unintelligible handwritng.
<br>
2. Then we chose two medicine names --> Hairbless & Lobate, which were on the presciption we had.
<br>
3. Then we manually wrote down the two medicine names in a style similar to the doctors handwriting.
<br>
4. Pre-processed the images and trained a model on this data.
<br>
5. Made the model predict for the actual snips of the doctors handwritng(these snips weren't used for training the model or validation).</b>
<br>
## 
