# Item-Response-Theory-IRT-Implementation-and-Application
This project aims to implement fundamental Item Response Theory (IRT) models and analysis techniques using the R programming language.
---
專案內容涵蓋古典測驗理論 (CTT) 的基礎分析，並深入探討 Rasch 模型 (1PL) 和廣義部分計分模型 (GPCM) 在二元計分及多級計分資料上的應用。透過實際程式碼和資料分析，本專案旨在展示 IRT 相較於 CTT 的優勢，以及 IRT 在測驗項目特性分析、受試者能力估計等方面的應用。
--
📕古典測驗理論 (CTT) 
    * 使用 R 語言進行基本項目統計量計算（難度、鑑別度）。
    * 使用 `CTT` 套件進行信度分析和項目分析。
    * 比較未修正與修正的項目鑑別度。
    * 探討 CTT 的局限性。
📘項目反應理論(IRT) 
    * **Rasch模型(1PL)：**
        * 基本概念與答對機率計算。
        * 項目特徵曲線(ICC)的繪製與解釋。
        * 使用 `TAM` 套件進行模型擬合與參數估計。
        * Wright Map 的繪製與解釋。
    * **廣義部分計分模型(GPCM)：**
        * 適用於多級計分資料的介紹。
        * 使用 `mirt` 套件分析 Big Five 人格量表資料。
        * 項目參數 (鑑別度、難度) 的解讀。
        * 選項特徵曲線和項目資訊函數的繪製與解釋。
