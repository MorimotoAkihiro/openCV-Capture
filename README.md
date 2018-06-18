cv2.VideoCapture()でVideoCaptureオブジェクトを取得. 引数はPCに接続されているカメラの番号を指定. （一台しか接続されていないときは0）

while文を使いカメラから連続的に画像を取得する.capture.read()でカメラから1コマのデータを取得. それをframeに代入してcv2.imshow()で画像の表示. 画像が表示されてる状態で'q'をタイプするとwhileを抜けるようにする.

whileを抜けるとcapture.release()でVideoCaptureの終了. cv2.destroyAllWindows()で開いたウィンドウも閉じる.

引用　https://weblabo.oscasierra.net/python/opencv-videocapture-camera.html
