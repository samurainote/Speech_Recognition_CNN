# Convolutional Neural Network: Speech Recognition　
## 畳み込みニューラルネットワークを用いた音声認識
![](https://www.di.ens.fr/~lelarge/dldiy/slides/lecture_8/images/speech_recognition_1.png)

## Introduction

Why CNN for Speech Recognition?

Because CNN can extract "Features" or "Patern" from .wav data!
In CNN, the hidden layer is composed of "convolution layer" and "pooling layer" as shown above.
The convolutional layer filters to nearby nodes in the previous layer to get a "feature map".
The pooling layer further reduces the feature map output from the convolutional layer into a new feature map.
In this case, which value of the region to focus on is used, but obtaining the maximum value as shown in the above figure also absorbs some misalignment of the .wav file.
Therefore, this processing has gained the universality to the position movement of the .wav file.

## Technical Preferences

| Title | Detail |
|:-----------:|:------------------------------------------------|
| Environment | MacOS Mojave 10.14.3 |
| Language | Python |
| Library | Kras, scikit-learn, Numpy, matplotlib, Pandas, Seaborn |
| Dataset | UrbanSound8K |
| Algorithm | CNN |

## Refference

- [Speech Recognition with Neural Networks](http://dkopczyk.quantee.co.uk/speech-nn/)
- [Keras Tutorial - Spoken Language Understanding](https://chsasank.github.io/spoken-language-understanding.html)
- [TensorFlow RNN Tutorial](https://www.svds.com/tensorflow-rnn-tutorial/)
- [Machine Learning is Fun Part 6: How to do Speech Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a)
- [機械学習は楽しい Part 6: ディープラーニングでの音声認識](https://qiita.com/daisukelab/items/4fdbf95c74e6206153c9)
- [TensorFlow Speech Recognition Challenge— Solution Outline](https://towardsdatascience.com/tensorflow-speech-recognition-challenge-solution-outline-9c42dbd219c9)
