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


### 一応、モジュールの吐き出し
pip freeze > requirements.tx