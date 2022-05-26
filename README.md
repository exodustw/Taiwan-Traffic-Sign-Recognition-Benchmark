# Taiwan Traffic Sign Recognition Benchmark (TTSRB)
## Introduction
這個資料集是模仿GTSRB (German Traffic Sign Recognition Benchmark) 製作的台灣版交通標誌辨識資料集，資料透過 Google 街景服務將道路周邊的交通標誌以截圖方式抓取下來。主要選擇的位置為台北市區、新竹市區、台中市區與北部國道周邊為主。蒐集超過 40 種不同的交通標誌，剔除採樣較少的幾種類型後，篩選出 27 個普遍出現的交通號誌作為蒐集重點。其中訓練集有711張影像，測試集則有377張，全部以人工方式進行標籤。
其中訓練集有另外製作data augmentation的版本，將原本711張影像擴充至20913張，主要用於CNN模型的訓練。
