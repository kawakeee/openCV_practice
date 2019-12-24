# openCV_practice
openCVをいじるリポジトリ

# 仮想環境の作成
python3 -m venv opencvEnv

# 仮想環境の立ち上げ
source opencvEnv/bin/activate

# モジュールのインストール
pip install -r requirements.txt


- face_detection.py
顔検出するだけ

- face_detection_cap.py
顔検出時のフレームをjpgで保存する
保存先は images/capture/

- face_detection_trim.py
顔検出時の顔検出部分をjpgで保存する
保存先は images/trim/

# モジュールの吐き出し
pip freeze > requirements.tx