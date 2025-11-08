# DataMining‑HW

## 專案簡介  
本專案為成功大學《Data Mining》課程作業與學習資料整理，內容涵蓋資料探勘的核心主題，包括關聯規則（Association Rule）、分類法（Classification）、群聚分析（Clustering）等。  
目的在於紀錄課程學習過程、整合筆記與程式實作，供未來學習與教學參考。

## 目錄結構  
```
DataMining‑HW/
├── AR_I.pdf / AR_II.pdf / AR_III.pdf          ← 關聯規則講義（由淺入深）  
├── ClassificationI.pdf / ClassificationII.pdf ← 分類法講義與範例  
├── ClusterI.pdf / ClusterII.pdf               ← 群聚分析講義與說明  
├── notebooks/                                ← 若有：實作 Notebook 或程式碼  
└── README.md                                 ← 本檔案  
```

## 執行環境與需求  
- Python 版本：3.8 或以上（若有程式實作部分）  
- 推薦工具：Jupyter Notebook 或 VS Code  
- 主要套件（如有實作）：  
  - `numpy`  
  - `pandas`  
  - `scikit‑learn`  
  - `matplotlib` / `seaborn`  
- 安裝方式：  
  ```bash
  pip install numpy pandas scikit‑learn matplotlib seaborn
  ```

## 資料說明  
本專案主要收錄：  
- **關聯規則（AR）系列**：由淺入深講解 Apriori、Support、Confidence、Lift 等概念與實例。  
- **分類法（Classification）系列**：涵蓋 Decision Tree、Naive Bayes、k‑NN 等演算法。  
- **群聚分析（Cluster Analysis）系列**：說明 K‑Means、Hierarchical Clustering 與 DBSCAN 概念與應用。  
每份 PDF 講義或 Notebook 對應不同週次課程主題，便於逐步理解資料探勘流程。

## 使用方式  
1. 若為講義，直接開啟 `.pdf` 檔閱讀。  
2. 若為實作檔（`.ipynb`），可在 Jupyter Notebook 中開啟並執行。  
3. 若欲重現程式環境，請先安裝需求套件後執行程式碼。  

## 學習重點與流程  
- **資料前處理（Preprocessing）**：缺值處理、標準化、編碼。  
- **關聯規則分析**：購物籃分析、規則挖掘、結果解讀。  
- **分類模型建立**：模型訓練、驗證、混淆矩陣與性能比較。  
- **群聚方法應用**：特徵選擇、K值選擇、視覺化分析。  
- **結果報告撰寫**：摘要每次實驗結果與結論。

## 成果展示  
- 各章節講義 PDF 檔案。  
- 可能包含 Notebook 範例與視覺化結果（如 Scatter Plot、Dendrogram 等）。  
- 若有實作，請在 `notebooks/` 中查看。  

## 注意事項  
- 本專案內容僅供學習、研究與教學示範用途。  
- 若引用資料或教材，請標註原課程與授課教師出處。  
- 若有外部資料集，請遵守其授權規範。  

## 未來改進方向  
- 將講義內容轉為互動式 Notebook 與程式教學。  
- 新增 Deep Learning 與 Time Series 分析章節。  
- 補充各章實作範例與 Kaggle 資料集應用。  

## 聯絡方式  
如有問題或建議，歡迎提交 Issue 或 Pull Request，謝謝！
