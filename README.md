# Human Activity Recognition using Smartphone Sensors

Machine Learning course project focused on recognizing human activities from smartphone accelerometer and gyroscope data.

<!-- TODO Add additional info -->

## Team Members

- Marijana Čupović — 1018/2025
- Jelena Bulajić — 1097/2024
- Tanja Gavrić — 1065/2025

## Dataset

The project uses the [Human Activity Recognition Using Smartphones](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones) dataset from the UCI Machine Learning Repository.

The dataset contains smartphone sensor measurements for six activities:

- Walking
- Walking upstairs
- Walking downstairs
- Sitting
- Standing
- Laying

<!-- TODO Add dataset properties. -->

## Methodology

### Data distribution

The data from 30 volunteers has been randomly split into **training and test** sets. As shown in the figure, approximately $70\%$ of the data has been assigned to the training set and $30\%$ to the test set. For **validation** purposes, $20\%$ of the training data has been randomly selected. 
![train_test_ratio](images/train_test_size_ratio.png)

The features are normalized and bounded within the interval $[-1, 1]$, as stated in the dataset description. Therefore, no additional standardization is required. The dataset contains no duplicate or missing values in either the training or the test set.

The **classes** are nearly balanced, with only minor variations. We would expect the same number of instances for the **WALKING_UPSTAIRS** and **WALKING_DOWNSTAIRS** classes, but there is a slight difference. One possible explanation is that it took the volunteers more time to climb upstairs than to descend, resulting in more sensor readings being recorded for the WALKING_UPSTAIRS class.
![class_distribution](images/class_distribution.png)

<!-- TODO Describe data analysis, preprocessing, train-validation-test split, models and hyperparameter selection -->

## Results

<!-- TODO Add evaluation metrics, confusion matrices, graphical model comparison and conclusions -->

## Installation

<!-- TODO Add setup instructions -->

## References

* Moore, J., & Ling, B.
  [Human Activity Recognition Using Smartphone Sensors](https://cs229.stanford.edu/proj2016/report/LingMoore-HumanActivityRecognitionUsingSmartphoneSensors-report.pdf).
  Stanford University, CS229 Final Project Report, 2016.


