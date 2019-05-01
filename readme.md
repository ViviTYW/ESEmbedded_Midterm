#### 2019.05.01

## Midterm ─ [Embedded System Development and OS Design](http://www.nc.es.ncku.edu.tw/course/embedded/)

#### 請 fork 此 repo ，並完成以下要求(依完整度部份給分)：

1. 使用 HSI 作為 PLL 之 clock source，將 system clock 調整為168 MHz，並使用 MCO2 輸出 (divided by 4)

2. 使綠色 LED 恆亮

3. 宣告一個 global uint32_t array，並給予初始值`{0xA, 0xB, 0xC, 0xD, 0xE, 0xF}`，使用 gdb 驗證此 global array 有成功被初始化(請將 gdb 畫面截圖存放至原始碼目錄下)

#### 請將結果 push 回自己的 github

#### 評分方式：

1. make
2. make flash
3. 綠燈恆亮
4. MCO2 輸出
5. 附圖

圖1

![image](https://github.com/ViviTYW/ESEmbedded_Midterm/blob/master/2019-05-01%2017-34-15%20%E7%9A%84%E8%9E%A2%E5%B9%95%E6%93%B7%E5%9C%96.png)

圖2

![image](https://github.com/ViviTYW/ESEmbedded_Midterm/blob/master/2019-05-01%2017-34-45%20%E7%9A%84%E8%9E%A2%E5%B9%95%E6%93%B7%E5%9C%96.png)

圖3

![image](https://github.com/ViviTYW/ESEmbedded_Midterm/blob/master/2019-05-01%2017-35-13%20%E7%9A%84%E8%9E%A2%E5%B9%95%E6%93%B7%E5%9C%96.png)

圖4

![image](https://github.com/ViviTYW/ESEmbedded_Midterm/blob/master/2019-05-01%2017-42-00%20%E7%9A%84%E8%9E%A2%E5%B9%95%E6%93%B7%E5%9C%96.png)
