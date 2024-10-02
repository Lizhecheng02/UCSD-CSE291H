## This Repo is for [UCSD 24Fall 291H Advanced Data-Driven Text Mining](https://shangjingbo1226.github.io/teaching/2024-fall-CSE291-DSC253-TM)

### Python Environment

#### 1. Install Packages

```b
pip install -r requirements.txt
```

### Prepare Data
#### 1. HomeWork 1

- You need to put ``nyt.csv`` and ``ag.csv`` under the **HomeWork1** folder.
- You need to put ``glove.6B.100d.txt`` under the **HW1 - word2vec** folder.

##### 1.1 You can download all data using Kaggle Api

```bash
export KAGGLE_USERNAME="your_kaggle_username"
export KAGGLE_KEY="your_api_key"
```

##### 1.2 Install unzip if you are using a GPU server

```bash
sudo apt install unzip
```

##### 1.3 Download datasets

```bash
kaggle datasets download -d lizhecheng/cse291h-hw-data
unzip cse291h-hw-data.zip
```

### Run Codes
#### 1. HomeWork 1

You only need to run the corresponding ``.ipynb`` file for different tasks.
