# Palm-ROI-Extraction

## 簡介
程式練習...

用於提取手掌感興趣區域（ROI）的程式

參考資料如下:

1.IEEE會議論文。[An effectual method for extraction of ROI of palmprints](https://ieeexplore.ieee.org/document/6398207)

2.他人參考會議論文，Python實作。[https://github.com/safwankdb/Effectual-Palm-RoI-Extraction/tree/master](https://github.com/safwankdb/Effectual-Palm-RoI-Extraction/tree/master)

上述提到的參考資料僅能處理左手，經過修改後能夠在小範圍內提取左右手ROI。

---

## 提取ROI步驟

1.圖像轉灰階
2.將手掌區域與背景分離(二值化加Otsu來決定分割閾值)

![2](image/2.png)


