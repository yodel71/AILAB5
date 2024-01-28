# 多模态情感分析

## Setup

requirements:

- numpy==1.25.4
  
- tensorflow==2.13.0
  
- pandas==1.3.5

- keras==2.13.1

- nltk==3.8.1

- torch==2.0.1 

- torchvision==0.15.2

- sklearn==1.0.1

You can simply run 

```python
pip install -r requirements.txt
```

## Repository structure
```python
|-- data # training and testing data (.txt & .jpg)
|-- data_json # data after data preprocessing
    |-- test.json # test data
    |-- train.json # train data
    |-- val.json # val data
|-- results
    |-- results.txt # final testing results
|-- README.md
|-- lab5.ipynb # all code 
|-- requirements.txt # packages required
|-- test_without_label.txt # testing data
|-- train.txt # train data label
```
