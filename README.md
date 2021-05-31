# SMS-spam-detection-using-natural-language-processing
The idea is to train a model that identifies spam and ham SMS text messages. The dataset we use is from the [UCI datasets](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) which contains a collection of more than 5 thousand SMS phone messages with ham or spam labels.

Basic data exploration and analysis is done to get interesting and useful insights about the data. Then **Navie Bayes** algorithm is used to train on the data. The model performs well on the test set with almost 97% accuracy. 

The classification report is as follows:

                  precision    recall  f1-score   support
         
         ham       1.00      0.99      0.99       979
        spam       0.94      0.98      0.96       136

    accuracy                            0.99      1115
    macro avg       0.97      0.98      0.98      1115
    weighted avg    0.99      0.99      0.99      1115


**Future work:** The trained model is already saved for future use. Future work includes creating a basic web application with Python Flask (HTML and CSS for frontend) that takes in an input text and outputs the model's prediction if the text is spam or ham. 
