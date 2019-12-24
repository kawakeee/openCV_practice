### openCV_practice
openCVをいじるリポジトリ

### 仮想環境の作成
python3 -m venv opencvEnv

### 仮想環境の立ち上げ
source opencvEnv/bin/activate

### モジュールのインストール
pip install -r requirements.txt

### 顔検出の手順(detection)
detectionのディレクトリに移動する
```
cd detection
```

```
python face_detect.py
```
顔検出するだけ

```
python face_detect_cap.py
```
顔検出時のフレームをjpgで保存する
保存先は images/capture/

```
python face_detect_trim.py
```
顔検出時の顔検出部分をjpgで保存する
保存先は images/trim/

### 顔認識の手順(recognition)
recognitionのディレクトリに移動する
```
cd recognition
```

※ get_myface/get_othersの実行前にimages/datasetフォルダ配下にmyfaceとothersフォルダを生成しておく。
自分の顔を収集する
```
python get_myface.py
```
images/dataset/myface配下に保存される

他人の顔を収集する
```
python get_others.py
```
images/dataset/others配下に保存される

### 一応、モジュールの吐き出し
pip freeze > requirements.tx


ブログ用に記事を分割

3ボンバシラ
datasetの準備

kerasの導入
mymodel.h5の準備

test用データの準備
predictionの実行
結果の確認