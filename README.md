
<font size=7 color="Purple">智慧安全手環-下水道專用</font>
===

## <font size=6 color="Orange">目錄</font>

* [摘要](#摘要)
* [研究動機](#研究動機)
* [研究目的](#研究目的)
* [文獻探討](#文獻探討)
* [研究方法及步驟](#研究方法及步驟)
* [參考文獻](#參考文獻)
* [發表評論](#發表評論)

## <font size=6 color="Orange">摘要</font>

>* **台灣的管線老舊(年久失修)**
>* **下水道工安不被重視**
>* **無人整合下水道必須的安全檢測裝置**
>>**主功能:**
>1. **手環<u><font size=3 color=red>(整合心律、血氧、沼氣)</font></u>**
>1. **軟體(接收手環回傳的資訊)**
>> **預計完成:<u><font size=3 color=red>手環偵測與軟體資訊整合成為一個下水道工人安全監測系統**</font></u>


## <font size=6 color="Orange">研究動機</font>
>* 在原有智慧手環(心率、血氧)上加裝沼氣感測器
>* 讓施工者得知道目前身體及環境狀況
>* 無人整合下水道必須的安全檢測裝置
>* 下水道工安頻傳，卻無人做出安全裝置
>* 提供監測者知道施工者的即時狀態
>* 以此智慧安全手環來保障施工人員的安全與方便監測人員的保護作業


## <font size=6 color="Orange">研究目的</font>

1. 提供智慧安全手環
   * 環境沼氣值監測 
   * 施工者心率監測 
2. 強波器(解決訊號距離問題) 
3. 安全監測軟體(供監測人員查看，並告知危險狀況，跳出警告) 
## <font size=6 color="Orange">文獻回顧</font>
*  <u><font size=6 color="Red">**血氧**</font></u>

> <font size=4 color="black">**透過用紅光LED照亮皮膚表面，透過分析皮膚反射光線來計算出血液中的氧氣含量是否低於90%以下**</font>
 
 
![](https://upload.cc/i1/2022/01/04/C6I8tk.png)
* <font size=6 color="blue">**無線強波器**</font>
> <font size=4 color="black">**優點:可增強訊號**</font>
> <font size=4 color="black">**缺點:受電力限制**</font>

* <font size=6 color="blue">**沼氣濃度監測器**</font>
> <font size=4 color="black">**沼氣是由微生物在厭氧環境下分解有機物質產生的氣體，可以 有效地將有機物質轉為能被利用的再生能源，甲烷25-30%會使人麻醉，70%就會導致缺氧面窒息死亡。**
![](https://upload.cc/i1/2022/01/11/Z2iTHF.png)
</font>

* <font size=6 color="blue">**視窗軟體監測:**</font>
> <font size=4 color="black">**Python Tkinter 模組，此模組是TK GUI整合到Python中的GUI開發套件Tkinter自帶Python的GUI套件，功能簡單但效能可能更好。**
</font>

 <font size=6 color="Orange">**文獻探討:**</font>
 
><font size=4 color="black">**市面上有許多的智能手環例如小米手環，但卻只有心率和血氧檢測卻沒有沼氣偵測，我認為我們所開發的智慧安全手環不僅能夠保有市面上基本的血氧和心率偵測還多增加沼氣偵測值和方便監控者觀看的監控軟體，可提供下水道施工人員以及監測者雙方有效的安全檢測及警報。**
</font>

<font size=6 color="Orange">研究方法及步驟</font>
---
![](https://upload.cc/i1/2022/01/11/0KnVqh.png)

<font size=5 color="Orange">**1.傳輸通訊協定(藍芽UDP+強波器)**</font>
![](https://upload.cc/i1/2022/01/04/HIvm72.png)
<font size=5 color="Orange">**2.視窗軟體監測程式**</font>
![](https://upload.cc/i1/2022/01/04/ZqWrRb.png)






* <U><font size=6 color="blue">**手環-施工者保護**</font></U>



><font size=4 color="black">1. 模組整合(蜂鳴器、心率、血氧模組、沼氣、微型馬)</font>
><font size=4 color="black">2. 啟動、確認整合按鈕</font>
><font size=4 color="black">3. LED燈號顯示</font>


* <U><font size=6 color="RED">**視窗軟體-監測者監控**</font></U>
><font size=4 color="black">1.藍芽傳輸</font>
><font size=4 color="black">2.UDP傳輸協定傳送</font>
><font size=4 color="black">3.血氧、心率、沼氣值顯示</font>
><font size=4 color="black">4.警告訊息挑出顯示</font>
><font size=4 color="black">5.市用強波器增強訊號</font>
## <font size=6 color="Orange">預期成果</font>
![](https://upload.cc/i1/2022/01/03/k4ngZw.jpg)
## <font size=5 color="Orange">*預期功能:*</font>
>**<u><font size=4 color="Orange">手環-施工者保護</font></u>**

>**1.模組整合(蜂鳴器、心率、血氧模組、沼氣、微型馬達)**
>**2.施工者可利用按鈕跟監控人員確認自身有意識**
>**3.LED燈號顯示(<u><font size=3 color="Oran">綠燈:安全</font></u>、<u><font size=3 color="Orange">黃燈:稍微危險</font></u>、<u><font size=3 color="red">紅燈:危險</font></u>)**

>**<u><font size=4 color="Orange">視窗軟體-監測者監控</font></u>**

>**1.心率、血氧、沼氣其中一項超標跳出警示**
>**2.可在視窗軟體上得知施工者的心率及血氧數值及環境沼氣值**

<font size=6 color="Orange">參考文獻</font>
---
高雄下水道沼氣害2命 工人妻搥胸崩潰癱倒急診室
https://www.chinatimes.com/realtimenews/20201202001091-260402?chdtv
電腦網路學習平台
http://www.ablmcc.edu.hk/~scy/CIT/network/Elearning_S2_3.htm
血氧
https://www.taiwansensor.com.tw/product/arduino-max30100-%E8%84%88%E6%90%8F%E8%A1%80%E6%B0%A7%E5%84%80-%E5%BF%83%E7%8E%87pulse-oximeter-heart-rate-%E6%84%9F%E6%B8%AC%E5%99%A8%E6%A8%A1%E7%B5%84/
強波器
https://www.totolink.tw/products_view/EX1200T
傳感器
https://www.winsensor.com/dianjiezhi/MG812dghCO2cgq_770.html
## <font size=6 color="008F8F">發表評論</font>

:::info
**有任何缺漏?** 發表評論!
:::


###### tags: `Templates` `Documentation`