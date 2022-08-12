# yolov3を触ってみる

## インストール

前回同様windows機にanacondaをインストールした状況で、anaconda promptを開いて、以下を実行
```
conda create -n yolov3test python==3.8
conda activate yolov3test
git clone https://github.com/ultralytics/yolov3
cd yolov3
pip install -r requirements.txt
pip install notebook
jupyter notebook
```

## 学習済みモデルで物体検出を実行

次を実行する
```
detect.py
```
実行後

C:\Users\toru.hishinuma\Desktop\yolov3\data\images

にある入力データに対して物体検出した結果が

C:\Users\toru.hishinuma\Desktop\yolov3\runs\detect\exp

のフォルダに出力される。
