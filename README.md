# CNN圖形辨識
* Yann LeCun 被譽為 Deep Learning 的三巨頭之一。他的 CNN (Convolutional Neural Networks) 是讓 Neural Network 重新受到重視的主因之一。

# 目錄
* 準備資料
* 準備數據
* 打造CNN
* 進行作業
# 準備資料
* 準備一個可以打開google colab 的賬號
* 由tf.Keras讀入mnist數據庫(也可以直接安裝tensorflow)
* 輸入的每筆資料形式要從(28,28)換成(28,28,1)
# 打造CNN
* 做3次convolution,每次都接max-pooling
* filter大小都是3x3,max-pooling都用2x2為一小區塊
* 只有1個隱藏層,使用200個神經元

