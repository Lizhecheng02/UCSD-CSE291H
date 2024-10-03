## This Repo is for [UCSD 24Fall 291H Advanced Data-Driven Text Mining](https://shangjingbo1226.github.io/teaching/2024-fall-CSE291-DSC253-TM)
### Author: [Zhecheng Li](https://github.com/Lizhecheng02) && Professor: [Jingbo Shang](https://shangjingbo1226.github.io/)

### Python Environment

#### 1. Install Packages

```b
pip install -r requirements.txt
```

### Prepare Data
#### 1. HomeWork 1

- You need to put the ``nyt.csv`` and ``ag.csv`` files under the **HomeWork1** folder.
- You need to put the ``glove.6B.100d.txt`` file under the **HW1 - word2vec** folder.

##### 1.1 You can download all data using Kaggle Api

```bash
export KAGGLE_USERNAME="your_kaggle_username"
export KAGGLE_KEY="your_api_key"
```

##### 1.2 Install unzip if you are using a GPU server

```bash
sudo apt install unzip
```

##### 1.3 Download datasets ([Link](https://kaggle.com/datasets/c4ada776d9cc4c0af88e420adf09b106c2ef1beb220e12c15c9ad1b9bc4917cb))

```bash
kaggle datasets download -d lizhecheng/cse291h-hw-data
unzip cse291h-hw-data.zip
```

### Run Codes
#### 1. HomeWork 1

You only need to run the corresponding ``.ipynb`` file for different tasks.

### Code Explainations
#### 1. HomeWork 1
- You should fit your `vectorizer` only on the ``training dataset``; otherwise, it could lead to data leakage.
- To fine-tune any transformer-based models on **HuggingFace**, you can either implement the training process from scratch with manual loss backpropagation (as shown in the `src.ipynb` file) or use the `Trainer` class with customizable parameters to complete the process (as shown in the `trainer.ipynb` file).
- You can try different parameters for each ``.ipynb`` file and see how the results change.