# Introduction

Neural Machine Translation (NMT) is an end-to-end learning approach for automated translation. Its strength comes from the fact that it learns the mapping directly from input text to associated output text. It has been proven to be more effective than traditional phrase-based machine translation, which requires much more effort to design the model. On the other hand, NMT models are costly to train, especially on large-scale translation datasets. They are also significantly slower at inference time due to the large number of parameters used. Other limitations are its robustness when translating rare words and failing to translate all parts of the input sentence. To overcome these problems, there are already some solutions, such as using the attention mechanism to copy rare words

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.
```bash
$ pip install -r requirements.txt
```

## Train model

Select the location to save the model in file translate 
Save file model to ``checkpoint-trans/...``

## RUN test
```bash
$ flask run 
```

