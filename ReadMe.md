# Kaggle - SMS Spam Classification

###### Detect spam in sms messages!  An exercise for course of ML at Imperial College London.

src: https://www.kaggle.com/c/sms-spam-classification/data

### Description

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

## Acknowledgments

We thank Tiago A. Almeida, José María Gómez Hidalgo and Akebo Yamakami for providing this dataset. 