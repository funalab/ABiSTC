# ABiS Training Course

本ページは [**AIによる生物画像解析トレーニングコース**](https://sites.google.com/view/abistc2019) の講義資料である。
本資料を実践することで、ディープラーニングを用いた生物画像処理技術の初歩的な知識や実践方法を学ぶことができる。
本資料はすべて Jupyter notebook (iPython notebook) により作成されている。


## Installation

```sh
% git clone https://gitlab.com/funalab/abistc.git
```

本資料のコードは、`Python 3.6.3` と `requirements.txt` に列挙されているパッケージを必要とする。  
以下のように、virtualenvを利用して環境を構築することができる。

```sh
% pyenv virtualenv 3.6.3 <my/virtualenv>
% pyenv shell <my/virtualenv>
% cd <path/to/ABiSTC>
% pyenv exec pip install -r requirements.txt
```

## 資料構成

1. CNNを用いた細胞画像分類 (classification_training.ipynb)  
2. CNNを用いた細胞画像セグメンテーション (segmentation_training.ipynb)