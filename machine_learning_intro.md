##### Reference : https://developers.google.com/machine-learning/intro-to-ml

## Introduction to Machine learning

Machine learning (ML) powers some of the most important technologies we use, from translation apps to autonomous vehicles. This course explains the core concepts behind ML.
ML offers a new way to solve problems, answer complex questions, and create new content. ML can predict the weather, estimate travel times, recommend songs, 
auto-complete sentences, summarize articles, and generate never-seen-before images.

* In basic terms, ML is the process of training a piece of software, called a model, to make useful predictions or generate content (like text, images, audio, or video) from data.

*  For example, suppose we wanted to create an app to predict rainfall. We could use either a traditional approach or an ML approach.
  Using a traditional approach, we'd create a physics-based representation of the Earth's atmosphere and surface, computing massive amounts of fluid dynamics equations. This is incredibly difficult.

* Using an ML approach, we would give an ML model enormous amounts of weather data until the ML model eventually learned the mathematical relationship between weather patterns that produce differing amounts of rain.
We would then give the model the current weather data, and it would predict the amount of rain.

## Types of ML Systems
ML systems fall into one or more of the following categories based on how they learn to make predictions or generate content:

* Supervised learning
* Unsupervised learning
* Reinforcement learning
* Generative AI


### Supervised learning
Supervised learning models can make predictions after seeing lots of data with the correct answers and then discovering the connections between the elements in the data that produce the correct answers. This is like a student learning new material by studying old exams that contain both questions and answers. Once the student has trained on enough old exams, the student is well prepared to take a new exam. These ML systems are "supervised" in the sense that a human gives the ML system data with the known correct results.

Two of the most common use cases for supervised learning are regression and classification.

 
- Regression
 A regression model predicts a numeric value. For example, a weather model that predicts the amount of rain, in inches or millimeters, is a regression model.

 <img width="1029" height="227" alt="Screenshot 2025-11-02 at 7 03 11 AM" src="https://github.com/user-attachments/assets/d7b3a12d-58ce-4495-84aa-ca32ac1fba27" />


- Classification

 Classification models predict the likelihood that something belongs to a category. Unlike regression models, whose output is a number, classification models output a value that states whether or not something belongs to a particular category. For example, classification models are used to predict if an email is spam or if a photo contains a cat.

  Classification models are divided into two groups: binary classification and multiclass classification. Binary classification models output a value from a class that contains only two values,    for example, a model that outputs either rain or no rain. Multiclass classification models output a value from a class that contains more than two values, for example, a model that can output   either rain, hail, snow, or sleet.


## Unsupervised learning

Unsupervised learning is a type of machine learning where the computer is given a bunch of data without any labels or correct answers. It has to figure out patterns, structures, or groupings in the data all by itself

example: Imagine dumping a huge pile of random fruits (apples, oranges, bananas, grapes) on the table in front of a kid who's never seen them before. You don't say "these are red and round, group them as apples." The kid just looks at shapes, colors, sizes, and naturally sorts them into piles of similar fruits.
That's unsupervised learning—the machine discovers hidden patterns on its own.

The most popular way unsupervised learning works is through ### clustering. The computer groups similar data points together into "clusters" based on how close or alike they are.



