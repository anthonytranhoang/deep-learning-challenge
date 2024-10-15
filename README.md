# deep-learning-challenge

## Project Overview
The Charity Donation Predictor is a deep learning model that predicts the likelihood of organizations receiving funding based on various features. The model uses historical data to train on features like application type, organization classification, income categories, and more, helping to make informed decisions about future charity donations.

This project is designed to help streamline the charity funding process by predicting which organizations are likely to receive donations, thus improving efficiency in the allocation of resources.

With a csv containing more than 34,000 organizations received from Alphabet Soup over the years, I have created a predictive model. 

## Results
The model was trained on 10+ epochs and achieved the following performance metrics on the test set:
Because of low GBS, I could not do a lot of epochs and did 3 more tests which failed. 

epochs=10

hidden_nodes_layer1 = 5

hidden_nodes_layer2 = 5

Loss: 0.5424

Accuracy: 68.30%

These results indicate that the model can accurately predict charitable donations at a moderately high rate.
