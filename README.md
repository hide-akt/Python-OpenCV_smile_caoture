# Python-OpenCV_smile_caoture
Python+OpenCVにてWebcamの映像をキャプチャし笑顔を認識した時に指定したフォルダに画面キャプチャしたpngデータを生成するプログラムです。
※大量のpngデータが生成されるのでご注意ください。

#環境
Mac macOS Big Sur ver.11.4

#Python
Python 3.8.8

#OpenCV
PythonからOpenCVを使うためにはOpenCVPythonを必要なのでインストールします。 pip install opencv-python

opencv-python==4.5.2.54

#カスケード型分類器
顔認識させるために必要なカスケード分類器は以下をCloneして用意しました。 https://github.com/opencv/opencv/
