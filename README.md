# Sentiment Classifier
## An awesome blend between Machine Learning and Graphical User Interface

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project aims to combine Machine Learning with a Graphical User Interface. It takes a review/feedback as an input from the user through a Graphical User Interface and passes the review/feedback into our already trained Machine Learning model and then our model will predict if the snetiment of the feedback is Positive or Negative and even give us the probabilities of the sentiment being Positive and Negative. We then present all of the information in a nice presentable manner to the user.


![Sentiment Classifier Screen Shot][product-screenshot]
![Sentiment Classifier Positive Prediction Screenshot]
![Sentiment Classifier Negative Prediction Screenshot][product-negative-screenshot]



Procedure:

* I used a dataset of 10,000 cutomer reviews to train my Machine Learning Models.
* Split the data to train and test and evenly distributed the positive and negative categorizes among them to minimize biasness. 
* Created Bag of words using CountVectorizer.
* Passed the training data to Linear SVM, Decision Trees, Naïve Bayes, and Logistic Regression algorithms using Sklearn. 
* Then evaluated their score, SVM came out with the best accuracy of about 80.77%
* Checked the F1 score of SVM to ensure that there is no biasness in our model.
* Decided to go on with SVM.
* Defined a function "model_run" to run predict function on svm for "feedback" input by the user.
* Created a basic GUI using Tkinter.
* Assigned the function "model_run" to be called everytime the user clicked the "Classify" button.
* Formatted the response and presented it to the user in a nice presentable way.


### Built With

This project was built entirely on Python.

* [Python](https://www.python.org)

### Libraries Used

* [argparse](https://docs.python.org/3/library/argparse.html)
* [open-cv](https://opencv.org/)
* [numpy](https://numpy.org/doc/stable/)
* [pandas](https://pandas.pydata.org/docs/)


<!-- CONTACT -->
## Contact

Your Name - [@puneet_arora_14](https://twitter.com/puneet_arora_14)

Project Link: [https://github.com/apuneet839/Feedback_Classifier](https://github.com/apuneet839/Feedback_Classifier)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-url]: https://www.linkedin.com/in/puneet-arora-1401
[product-screenshot]: images/Sentiment_classifier_default.png
[product-positive-screenshot]: images/Sentiment_classifier_positive.png
[product-negative-screenshot]: images/Sentiment_classifier_negative.png
