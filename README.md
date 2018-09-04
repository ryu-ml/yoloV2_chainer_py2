# YOLOv2（Chainer, Python2バージョン）
YOLOv2は、これまで速度、精度共に世界最高レベルのリアルタイム物体検出手法と
言われてきています。

本リポジトリは、<a href="https://github.com/leetenki">leetenki</a>さんの
<a href="https://github.com/leetenki/YOLOv2">YOLOv2の論文をChainer上で再現実装したもの</a>をもとに、Python2バージョンで
編集したものです。


## 環境
- Ubuntu 16.04.1 LTS (GNU/Linux 4.4.0-59-generic x86_64)
- Anaconda 2.4.1 or nvidia-docker
- Python 2.7.X
- OpenCV 2.4 + (?)
- Chainer v3
- CuPy v2
- CUDA V8.0



## YOLOv2の訓練済みモデル(完全版)実行手順
<a href="https://github.com/leetenki">leetenki</a>さんの、darknetオリジナルの重みパラメータファイルを
chainerで読み込んで実行するための手順ページです。

darknetオリジナルの重みパラメータファイルはこちら：
<a href="https://cloud.mail.ru/public/KzyC/B9FVxwyw9">重みパラメータファイルへのクラウドドライブのリンク</a>
（ロシア語UIページなので翻訳してください。ファイルは約257MBあります。ダウンロード時間かかります。）

オリジナルの重みパラメータファイルを読み込んで実行するための手順ページ：
[YOLOv2の訓練済みモデル実行手順](https://github.com/leetenki/YOLOv2/blob/master/YOLOv2_execute.md) (2018/09/05)
