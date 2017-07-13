[Qiita記事]() | [haltaro](https://haltaro.github.io)

[Deep learning nanodegree foundation](https://github.com/udacity/deep-learning)で公開されているjupyter notebookを日本語化するプロジェクトです．
`*_j.jpynb`は，`*.jpynb`の日本語訳を表します．
また，2017年7月8日時点の最新版のnotebookを翻訳対象とします．

# 目次

Notebookは，tutorialとprojectに大別されます．Tutorialの練習問題には解答が用意されていますが，projectの練習問題には解答が用意されていません．これは，後者が[Udacity](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101)受講者向けの課題であるためです．そこで本プロジェクトでは，主なtopicのtutorialを翻訳の対象とします．

以下のように，独断で5グループに分類します．（）は原題です．

## 入門編

* TFlearn入門（Intro to TFlearn）
* TensorFlow入門（Intro to TensorFlow）
* NumPyで評判分析（Sentiment analysis with Numpy）
* 性能向上のための変数初期化（Weight initialization）

## Convolutional neural networks

* 転移学習（Transfer learning with ConvNet）

## Recurrent neural networks

* RNN入門（Character-wise RNN）
* Word2Vec（Embeddings）
* RNNで評判分析（Sentiment analysis RNN）
* Seq2Seq（Sequence to sequence）

## Generative adversarial networks

* 自己符号化器（Autoencoder）
* MNISTでGAN（Generative Adversatial Network on MNIST）
* Deep Convolutional GAN（Deep Convolutional GAN）

## その他

* Tensorboard入門（Tensorboard）
* [DQNで強化学習](https://github.com/haltaro/deep-learning-in-japanese/blob/master/reinforcement/Q-learning-cart_j.ipynb)（[Deep Q-learning](https://github.com/udacity/deep-learning/blob/master/reinforcement/Q-learning-cart.ipynb)）: Deep Q-learning networkをtensorflowで実装して，OpenAI GymのCat-Poleゲームに挑戦します． 
* Batch normalization（Batch normalization）

# 環境

各ディレクトリの`requirements.txt`は，notebookを実行するのに最低限必要な環境を示します．

## `pip`

`pip3 install -r requirements`で環境構築可能です． 

## `Conda`

`environments`ディレクトリに`Conda`用の環境ファイルがあります．これらの環境ファイルはプラットフォーム依存ですのでご注意ください．

# License

MIT License

Copyright (c) 2017 Udacity, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
