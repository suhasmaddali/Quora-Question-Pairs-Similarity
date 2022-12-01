# ⁉️ Quora Question Pair Similarity

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Problem Statement

```diff
+ This project was developed with the help of https://www.appliedaicourse.com/ based in India. 🙂
```

The problem is about identifying whether a given question already exists in the repository of questions asked in __Quora__. If the given question is similar __semantically__ and the meaning, the __machine learning algorithms__ must accurately identify whether the questions are duplicates of one another. 

In __Quora__, we find that a lot of people ask questions every second. It is important that proper steps are taken to remove questions that are similar to the previously asked questions. If a similar question is asked with a change in wording, it would be appropriate to attach answers to the previously asked question that was similar to this question. This would save a lot of time and memory space on the part of Quora and minimize its expenses. 

![](https://github.com/suhasmaddali/Images/blob/main/emily-morter-8xAA0f9yQnE-unsplash.jpg)

## Machine Learning and Data Science

Since there are questions that could be semantically and structurally similar to the already asked questions, it would be great to classify those questions as being equivalent and vice-versa. Generating a dataset of 2 questions and an output variable of whether it is a duplicate of the other is handy for machine learning purposes. 

Therefore, we build our data on the basis of achieving reasonable accuracy on whether a given question is a duplicate of the other or not. After generating this data, it is important to convert the question text into a mathematical vector which could later be used and trained with the aid of machine learning models. 

## Machine Learning Models 

Since the output variable that is considered is a discrete variable (whether similar or not similar), classification models were used for the predictions. Below are some of the machine learning and deep learning models used to predict whether a pair of questions are similar or not. 

* [__Support Vector Machines (SVM)__](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
* [__Logistic Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
* [__Gradient Boosted Decision Trees (GBDT)__](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
* [__Random Forests__](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

## Outcomes

* After converting a given text to a list of vectors and performing feature engineering, the machine learning models used were __Support Vector Machines__, __Logistic Regression__, __Gradient Boosted Decision Trees__ and __Random Forests__. 
* After training with these models, machine learning predictions were generated with an accuracy of about __95 percent__ on the cross-validation data. 
* With the best model, therefore, it is possible to deploy it in real-time in classifying the text as a duplicate or non-duplicate. 

## Future Scope 

* More data from various sources could be added that help the algorithm predict well on the test data (unseen data).  
* Algorithms such as __BERT__ and __ROBERTA__ can be added to improve the predictive performance of the models. 
* Deep learning models with __various architectures__ should be used to improve the overall performance. 
* An __API__ could be created for users to make use of the best models in their application in classifying questions. 


## 👉 Directions to download the repository and run the notebook 

This is for the Washington Bike Demand Prediction repository. But the same steps could be followed for this repository. 

1. You'll have to download and install Git which could be used for cloning the repositories that are present. The link to download Git is https://git-scm.com/downloads.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(14).png" width = "600"/>
 
2. Once "Git" is downloaded and installed, you'll have to right-click on the location where you would like to download this repository. I would like to store it in the "Git Folder" location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(15).png" width = "600" />

3. If you have successfully installed Git, you'll get an option called "Gitbash Here" when you right-click on a particular location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(16).png" width = "600" />


4. Once the Gitbash terminal opens, you'll need to write "Git clone" and then paste the link to the repository.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(18).png" width = "600" />

5. The link to the repository can be found when you click on "Code" (Green button) and then, there would be an HTML link just below. Therefore, the command to download a particular repository should be "Git clone HTML" where the HTML is replaced by the link to this repository. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(17).png" width = "600" />

6. After successfully downloading the repository, there should be a folder with the name of the repository as can be seen below.

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(19).png" width = "600" />

7. Once the repository is downloaded, go to the start button and search for "Anaconda Prompt" if you have anaconda installed. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(20).png" width = "600" />

8. Later, open the Jupyter notebook by writing "Jupyter notebook" in the Anaconda prompt. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(21).png" width = "600" />

9. Now the following would open with a list of directories. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(22).png" width = "600" />

10. Search for the location where you have downloaded the repository. Be sure to open that folder. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(12).png" width = "600" />

11. You might now run the .ipynb files present in the repository to open the notebook and the python code present in it. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(13).png" width = "600" />

That's it, you should be able to read the code now. Thanks. 


