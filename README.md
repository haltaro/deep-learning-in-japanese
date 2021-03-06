[Qiita記事](http://qiita.com/haltaro/items/3a17c5c574f0c1631012) | [haltaro](https://haltaro.github.io/projects)

[Deep learning nanodegree foundation](https://github.com/udacity/deep-learning)で公開されているjupyter notebookを日本語化するプロジェクトです．
`*_j.jpynb`は，`*.jpynb`の日本語訳を表します．
また，2017年7月13日時点の最新版のnotebookを翻訳対象とします．

![dlnd](fig/dlnd.png)

# 目次

notebookは，tutorialとprojectに大別されます．tutorialの練習問題には解答が用意されていますが，projectの練習問題には解答が用意されていません．これは，後者が[Udacity](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101)受講者向けの課題であるためです．そこで本プロジェクトでは，一つのnotebookとして完結している，tutorialを翻訳の対象とします．

以下のように，独断で5グループに分類します．（）は原題です．

## 入門編

* TensorFlow入門（Intro to TensorFlow）
* [TFLearnで評判分析](https://github.com/haltaro/deep-learning-in-japanese/blob/master/intro-to-tflearn/TFLearn_Sentiment_Analysis_Solution_j.ipynb)（[Sentiment analysis with TFLearn](https://github.com/haltaro/deep-learning-in-japanese/blob/master/intro-to-tflearn/TFLearn_Sentiment_Analysis_Solution.ipynb)）: TensorFlowラッパー[TFLearn](http://tflearn.org/)で，映画レビューの評判分析に挑戦します．
* TFLearnで手書き文字認識（Handwritten number recognition with TFLearn and MNIST）
* 性能向上のための変数初期化（Weight initialization）

## Convolutional neural networks

* 転移学習（Transfer learning with ConvNet）

## Recurrent neural networks

* RNN入門（Character-wise RNN）
* Word2Vec（Embeddings）
* [RNNで評判分析](https://github.com/haltaro/deep-learning-in-japanese/blob/master/sentiment-rnn/Sentiment_RNN_Solution_j.ipynb)（[Sentiment analysis with RNN](https://github.com/haltaro/deep-learning-in-japanese/blob/master/sentiment-rnn/Sentiment_RNN_Solution.ipynb)）：TensorFlowでlong short term memoryベースのrecurrent neural networkを実装して，映画レビューの評判分析に挑戦します．
* [Seq2Seq](https://github.com/haltaro/deep-learning-in-japanese/blob/master/seq2seq/sequence_to_sequence_implementation_j.ipynb)（[Sequence to sequence](https://github.com/haltaro/deep-learning-in-japanese/blob/master/seq2seq/sequence_to_sequence_implementation.ipynb)）：TensorFlowでSeq2Seqを実装して，入力文字列をソートするモデルを実装します．

## Generative adversarial networks

* 自己符号化器（Autoencoder）
* MNISTでGAN（Generative Adversatial Network on MNIST）
* Deep Convolutional GAN（Deep Convolutional GAN）
* GANで半教師あり学習（Semi-supervised learning）

## その他

* Tensorboard入門（Tensorboard）
* [DQNで強化学習](https://github.com/haltaro/deep-learning-in-japanese/blob/master/reinforcement/Q-learning-cart_j.ipynb)（[Deep Q-learning](https://github.com/haltaro/deep-learning-in-japanese/blob/master/reinforcement/Q-learning-cart.ipynb)）: TensorFlowでDeep Q-learning networkを実装して，OpenAI GymのCat-Poleゲームに挑戦します． 
* Batch normalization（Batch normalization）

# 環境

各ディレクトリの`requirements.txt`は，notebookの実行に最低限必要な環境を示します．

## `pip`

`pip3 install -r requirements`で環境構築可能です． 

## `Conda`

`environments`ディレクトリに`Conda`用の環境ファイルがあります．お使いのプラットフォームに適したファイルをご利用ください．

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
