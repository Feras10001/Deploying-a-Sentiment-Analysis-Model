# Deploying-a-Sentiment-Analysis-Model
Deploying a Sentiment Analysis Model in Amazon SageMaker

---------------------------------------------------------

**Project motivation:** Building Sentiment-Analysis-Model and deploying using Amazon sagemaker by having the user sending a reveiw through a website and recieve an output telling whether the reveiw is positive or negative review. The model is an RNN (Recurrent Neural Network). 

In summary the goal will be to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.

----------------------------------------------------------

**Requirements:**
The following libraries are included:
* numpy
* torch
* helper
* sagemaker
* collections
* pickle
* sklearn
* os
* nltk
* bs4
* re

----------------------------------------------------------

**Files in the repository:**
* [SageMaker Project.ipynb]: containes the full code
* [Report HTML]: Code viewed from browser
* [Index]:website for user interface, where the user type his review and recieve a result telling if the review positive or negative (the website is not functional as the situp in Amazon service is deactivated)
* [model]: contains the RNN model
* [train]: contains the code for training the RNN model
* [predict]: contains the code for using the RNN model for predcition
* [review snapshot]:snapshot of a review typed in the website

*data used:* it was provided by Udacity

-----------------------------------------------------------------

**Results:**
You can find a summary of my result either at the presentation, report, of my blog post.

-------------------------------------------------------------------

**Acknowledgement:**
This project was built over the data availed from Udacity.
