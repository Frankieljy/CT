# 论文题目 [ArXiv]()

作者列表

##### **Abstract**

In this research, we conducted predictions in two categories: AD and NC. Patients were divided into 2 data sets. One was used to train the model and the other was used to independently test the generated model. The training set was composed of 2 groups. The NC group included 11 cases. The AD group included 9 cases. Two categories, with a total of 4 cases of AD and 9 cases of NC, were also included in the independent test set. We used the above-mentioned 97 features, which were extracted from the training data set, to train our RF model, and then we evaluated the performance of the model on an independent set of test data. 



## 1. Installation

Clone this repo.

`https://github.com/Frankieljy/CT.git`

This code requires 

 `pip install pandas scikit-learn seaborn matplotlib numpy joblib`

## 2. Structure

- data/
  - train.csv
  - test.csv
- weights/
  - Random Forest_model.joblib
- README.md
- train.py
- test.py

## 3. Data

 In the data folder, we provide the 97 think features we used on the training as well as the test dataset.20 cases in train and 13 cases in test.



## 4. Inference Using Pretrained Model

Run the `test.py` file to test the model and generate evaluation metrics and confusion matrices:

`python test.py`



## 5 . Train Model

Run the `train.py` file to train the model:

`python train.py`



