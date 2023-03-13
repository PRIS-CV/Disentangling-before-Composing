# Disentangling-before-Composing

This repository provides dataset splits and code for Paper:

Disentangling before Composing: Learning Invariant Disentangled Features for Compositional Zero-Shot Learning

## Usage 

1. Clone the repo.

2. We recommend using Anaconda for environment setup. To create the environment and activate it, please run:
```
    conda env create --file environment.yml
    conda activate czsl
```

3. The dataset and splits can be downloaded from: [CZSL-dataset](https://drive.google.com/drive/folders/1ZSw4uL8bjxKxBhrEFVeG3rgewDyDVIWj).


4. To run DBC for UT-Zappos dataset:
```
    Training:
    python train.py --config config/zappos.yml

    Testing:
    python test.py --logpath LOG_DIR
```


**Note:** Most of the code is an improvement based on https://github.com/ExplainableML/czsl.
