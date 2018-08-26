# Kaggle - SMS Spam Classification

###### Detect spam in sms messages!  An exercise for course of ML at Imperial College London.

src: https://www.kaggle.com/c/sms-spam-classification/data

The code related to this Kaggle submission is in [A_kaggle_data_prediction.ipynb notebook](./A_kaggle_data_prediction.ipynb)

Also included is the complete dataset from uci.edu archives, for further learning and experiments. The code related to this can be [B_uci_edu_data_playbook notebook](./B_uci_edu_data_playbook.ipynb).



#### Description

First exercise of the course is classification of SMS messages into spam and ham.

Predictions provided by your model are expected to follow this format: 

```
Id,Label
0,0.7
1,0.3
2,0.6
3,0.0
...
```

The provided prediction is expected to be higher for **spam** messages.

- ROC AUC is used as a metric (metric is explained in the class).
- See the notebook provided during the course to start.
- Validation dataset is split in 2 equal parts: public and private. First is shown on the leaderboard, second is used to compute final standings.
- The amount of data available for training / testing is small. Keep this in mind.
- Teams with 2 members are allowed.



#### Acknowledgments

We thank Tiago A. Almeida, José María Gómez Hidalgo and Akebo Yamakami for providing this dataset. 



#### References

* [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
* [Spam Classifier in Python from scratch](https://towardsdatascience.com/spam-classifier-in-python-from-scratch-27a98ddd8e73)
* [Yandex Data School -  ML at Imperial 2016](https://github.com/yandexdataschool/MLatImperial2016/blob/6d5cdacdd57c33d7cb4916dab7e866291a27b2fa/1%20-%20Introduction%20to%20sklearn.ipynb)

* [Youtube -- Probability Theory - The Math of Intelligence #6 by Siraj Raval](https://www.youtube.com/watch?v=PrkiRVcrxOs)
* [Write SMS-spam detector with Scikit-learn](https://medium.com/@kopilov.vlad/detect-sms-spam-in-kaggle-with-scikit-learn-5f6afa7a3ca2)
* [Ben-Gurion University of Negev -- Classification of text documents: 20-Newsgroup Dataset](https://www.cs.bgu.ac.il/~elhadad/nlp17/Classification_20Groups_Sklearn.html)

