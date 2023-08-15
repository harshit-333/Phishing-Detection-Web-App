                               A Cloud-Based Machine-Learning Approach to Phishing URL

Description:

In this project, we are training a model to detect phishing websites using GradientBoost Classifier(GBC). Phishing websites are those which steal user's personal data(credentials,account informations etc) and use it to threaten the users. Gradient boosting is a machine learning technique used in regression and classification tasks, among others. It gives a prediction model in the form of an ensemble of weak prediction models, which are typically decision trees

Dataset:
Our dataset consists of a collection of website URLs for 11000+ websites. Each sample has 30 website parameters and a class label identifying it as a phishing website or not (1 or -1).

How to run:
First we have to run/compile the FeatureExtraction file as it is used to extract 30 features of the websites in order to feed it to our trained model.
Now you need to run the app.py file which is used to import model.pkl that is the saved model after training it. You will then get the link to the website which contains a text-box where you need to enter the site which you want to test. Clicking on the 'click here' button, you will be shown with the result whether the site is safe to go or not along with the site above the result. Then you can choose either to go further or step back.


  