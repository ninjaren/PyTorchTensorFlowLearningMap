# PyTorch / TensorFlow 學習地圖

PyTorch 與 TensorFlow 入門學習地圖：用生活化比喻拆解每個核心概念，兩套框架程式碼並排對照，從張量、自動微分、神經網路、訓練迴圈、資料管線到模型部署，最後還有一個從資料到可用分類器的完整範例。

## 特色

- **白話優先**：每個概念先用生活中的比喻講一次「這是在幹嘛」，再進技術細節。
- **兩套框架並排對照**：每一段範例都同時列出 PyTorch 與 TensorFlow 的寫法，方便直接比較兩種語言怎麼表達同一件事。
- **完整範例**：不只教個別概念，還有一頁把六個核心主題串成一條線，從下載真實資料、定義模型、訓練、存檔到包成可呼叫的函式。

## 怎麼看

純靜態網站，不需要安裝任何東西或啟動伺服器：

```bash
git clone https://github.com/ninjaren/PyTorchTensorFlowLearningMap.git
cd PyTorchTensorFlowLearningMap
```

直接用瀏覽器打開 [`home.html`](home.html) 即可開始瀏覽；也可以用 GitHub Pages 把整個 repo 發佈成網站。

## 章節

建議學習順序（1 → 6）：

1. [張量基礎](tensors/index.html) —— 張量其實就是「裝數字的容器」
2. [自動微分](autograd/index.html) —— 模型怎麼「知道」自己哪裡算錯
3. [建立神經網路](neural_networks/index.html) —— 把運算像堆積木一樣組起來
4. [訓練迴圈](training_loop/index.html) —— 模型怎麼一次又一次地「練習」
5. [資料管線](data_pipeline/index.html) —— 怎麼分批、打亂順序餵資料
6. [模型儲存與部署](model_persistence/index.html) —— 訓練好的模型怎麼存檔、接到實際應用

完整範例：

- [完整範例：手寫數字分類器](capstone/index.html) —— 把六塊積木接成一條線的端對端範例，程式碼全程加註解

延伸資源（不分先後、查閱用）：

- [進階方向路線圖](roadmap/index.html) —— CNN、Transformer、分散式訓練、ONNX
- [常用函式庫地圖](library_reference/index.html) —— torch.nn、tf.keras.layers 等常用模組速查

## 授權

[MIT License](LICENSE)
