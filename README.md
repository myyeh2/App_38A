<!--     驗證           --> 

![](Images/09-05-01.png)  
<!--   
# \[ { \color{Fuchsia}精\quad銳\quad矩\quad陣\quad計\quad算\quad求\quad解\quad器 : } \]  

## \[ { \color{Green} 【Sharp \, Matrix \, Solver \, - \, SMS】 } \]  
-->  

![](Images/09-05-02.png)  
<!--   
##### \[ { \color{Brown} R. W. Clough \, And \, Joseph \enspace Penzien \enspace "Dynamics \, of \,  Structures " } \] 

##### \[ { \color{Brown} 第一版從第202頁至203頁，使用 S\,M\,S\, 應用軟體實作並驗證} \]  
-->  

![](Images/09-05-03.png)  
<!--   
# \[ \]  

###  二階(r=2)且多個節點(m=3)的齊次微分方程式 ：  

### \( M * y_h''(t) + C * y_h'(t) + K * y_h(t) = d \)  

> \( 上式y_h(t)表示齊次解，d 是係數向量，與時間 t 無關，可由初始值或是邊界值求得。 \)  
 
### \( 已知數據如下: \)  

#### \(M=\begin{bmatrix}1 & 0 & 0 \\ 0 & 1.5 & 0 \\ 0 & 0 & 2 \end{bmatrix} \qquad C=\begin{bmatrix}0 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{bmatrix}\)  

#### \(K=\begin{bmatrix}600 & -600 & 0 \\-600 & 1800 & -1200 \\ 0 & -1200 & 3000 \end{bmatrix}\) 
-->  

![](Images/09-05-04.png)  
<!--   
#### \(InitValue=\begin{bmatrix} \dot{y_0}(0) \\ \dot{y_1}(0) \\ \dot{y_2}(0) \\ y_0(0) \\ y_1(0) \\ y_2(0) \end{bmatrix} = \begin{bmatrix}  0 \\  9 \\  0 \\ 0.5 \\ 0.4 \\ 0.3 \end{bmatrix}\)
-->  

![](Images/09-05-05.png)  
<!--    
### 系統(狀態)矩陣 \( { \color{red}A } \) 的求解，狀態變數的響應值(共計有m \(\ast\) (r + 1) 個)，即 \( { \color{fuchsia}H_{exp}(D, Q, t)；} \)   \( { \color{fuchsia} D是複數特徵值矩陣，Q是複數特徵向量矩陣，t是時間 } \)，請參考儲存庫 \( {\color{blue}Docs\_2A} \) ，即 README.md Markdown 檔案説明。 

## 狀態變數的響應值(即 變位、速度、和加速度)與視覺化的圖表，請參考本儲存庫中的相關檔案。   
-->  
