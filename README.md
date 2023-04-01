<!-- App_38A 儲存庫的内容   -->

# 【App_38A】Repository 儲存庫  

## 本測試是採用Ray W. Clough 和 Joseph Penzien "Dynamics of Structures" 結構動力學第202頁至203頁  

### 本書是本人學生時代的經典教科書，本例是[Homogeneous]方程式解，並不包含[Particular]特別解  

### 空間維度[Space Dimension]共有3個自由度（Degree Of Freedon m=3），狀態維度[State Dimension]是2個自由度(r=2)  

### 時間維度[Time Dimension]是時間序列(Time Series)可任選取時間。故整個系統矩陣是時間函數(mXr)X(mXr)的方陣  

### 求解6X6時間函數的矩陣，當時若時使用手算求解可能有困難？

### 本人在當時也完全無概念，如今使用系統特徵值和特徵向量(其預設值都是複數矩陣)，求解動態系統(State Space Response)  

### 在網路和文獻上，好像沒有人使用這種方式且使用程式碼實作求解，因本人能力有限，若有發現敬請<Email:myyeh2@xuite.net>給本人參考，在此表示謝意  

### 另從Wikipedia有關(State-Space Representation)，也僅有列出多空間自由度和一階狀態的微分方程式而已，沒有實際的求解法  

### 以上為本人於數十年前，在臺大土木系數次聼Ray W. Clough 教授演講之緣，在此表示對教授的尊敬  
