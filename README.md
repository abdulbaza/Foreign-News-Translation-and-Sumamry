# Foreign News Translation and Summarization

# Motivation

Machine translation is one of the most difficult parts of NLP, however
recent advancements in sequence to sequence model architecture, and the advent of Transformer encoder-decoder models (e.g., BERT, GPT-2, RoBERTa, XLNet, ALBERT, T5, ELECTRA) has improved translation results substantially

![Random GIF](https://media.giphy.com/media/VeWllmR9zfaco/giphy.gif) 

Moreover, models trained with OPUS (https://opus.nlpl.eu/), an open source project undertaken by the University of Helsinki and global partners to provide datasets
for especially low resource languages, have added further gains. This project will leverage language models trained on OPUS, for translation
while using Google Pegasus (https://arxiv.org/abs/1912.08777) for summarization.

#Requirements and Installation
Python 3.9.12

The project can be cloned on your device using the following command:
```git init```

```git clone https://github.com/abdulbaza/Recipe_Classifier.git```

After cloning into a directory of your choice

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following python packages:
```bash
pip install torch
pip install tensorflow
pip install transformers
pip install newspaper
pip install numpy
pip install pandas
```
The project is fully runable in jupyternotebook which can be accessed with the command on Linux 
 ```bash
 jupyter notebook
```

