# benkyo
windows想定

## python環境構築
1. Anacondaをインストールする

2. Anaconda promptを開き（画面左下の検索ボックスでanaconda promptと入力すれば出てくる）、以下を実行
```
conda create -n hogehogehoge python==3.8
conda activate hogehogehoge
pip install torch torchvision matplotlib ipywidgets widgetsnbextension
```

3. この`benkyo`リポジトリをダウンロード（githubページから`code`->`Download ZIP`とクリック）して、デスクトップ上に解凍（おそらく`benkyo-main`という名前になる）。


## jupyter notebook起動
1. Anaconda prompt上で、このリポジトリをダウンロードand解凍したところ移動する。
```
cd Desktop
cd benkyo-main
```

2. `hogehogehoge`環境でjupyter notebookを起動する（Anaconda prompt上で以下を実行）。
```
conda activate hogehogehoge
jupyter notebook
```
## リンク
* [数理・データサイエンス・AI教育強化拠点コンソーシアム](http://www.mi.u-tokyo.ac.jp/6university_consortium.html)
* [CS231n: Deep Learning for Computer Vision](http://cs231n.stanford.edu/schedule.html)
* [Computer Vision (CMU 16-385)](http://16385.courses.cs.cmu.edu/spring2021/courseinfo)
