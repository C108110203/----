---
title: 'Project documentation template'
disqus: hackmd
---

<font size=7 color="Purple">智慧安全手環(下水道專用)使用說明</font>
===
## <font size=6 color="Orange">產品介紹</font>
>>* **此手環為專門為下水道工程所開發，可提供施工者與監測者之間溝通的橋樑，請勿將此產品使用在下水道工程之外的使用環境。**

## <font size=6 color="Orange">1.手環簡介及功能</font>

>* **1.1	開始使用:施工者佩戴上手環後，把按鈕長按後手環即會自動配對裝有監測軟體(Python Tkinter)的電腦設備。**
>* **1.2	按鈕:連續短按按鈕為求救；長按按鈕為開關機。若本身監測值達到危險，需短按一下按鈕來回傳自身安全的資訊**
>* **1.3	LED:燈號分為3種(綠燈:安全、黃燈:稍微危險、紅燈:危險)，檢測指標包含了沼氣、心率、血氧，三項指標有其一超標即會亮燈。**
>* **1.4	警告:除了1.3項目說的LED燈號警示，本手環還有提供震動警告與聲音警告(蜂鳴器)，將會依據危險程度來決定震動強度與聲音頻率，來警告施工者是否須撤離下水道。**
>![](https://upload.cc/i1/2022/01/12/Q8MUBe.png) **(手環外觀)**
## <font size=6 color="Orange"></font>
>


## <font size=6 color="Orange">2.監控軟體簡介:</font>

2.1	**開始使用:等待手環配對成功，畫面上即會顯示三項數值，數值有在變動即為配對成功。**
2.2 **測試:請施工者連續短按按鈕，畫面上有跳出警告框即為連線成功。**
2.3 **警告:在施工者手環上偵測到的數值(沼氣、血氧、心率)來作為指標，三項其一有達到警告安全值即會跳出黃色警示框；有達到危險警告值時會跳出紅色警示框，若這兩種狀況施工者沒有短按一下按鈕確認是否安全，軟體部分的警告框將不會消除**
![](https://upload.cc/i1/2022/01/12/TUN0yG.png)
![](https://upload.cc/i1/2022/01/12/7F2sVZ.png)
* <font size=4 color="Red">**上為監控軟體介面圖**(包含警告視窗)</font>
## <font size=6 color="Orange">3.強波器:</font>


> <font size=4 color="black">**3.1 使用:將強波器裝上鋰電池，並將其開機，開機後即會搜尋手環訊號並連線，並同時將訊號發送給監測軟體端下**</font>
 
 
![](https://upload.cc/i1/2022/01/12/DcieHE.png)
* <font size=6 color="blue">**Python Tkinter安裝環境**</font>
> 

* <font size=5 color="blue">**為 Windows 安裝 Tk**</font>
> <font size=4 color="black">**自從 Python 3.1 之後，Tkinter 就被包括在 Python標準庫中。你必須確保自己的 Python 版本支援 Tk 8.5 或者更高版本。本教學使用 Python 3.x。請在 Python [官網下載](https://www.python.org/downloads/)最新版 Python**

</font>


* **安裝之後，需要驗證 tkinter 版本是否正確。開啟 cmd，輸入 python 進入互動介面，並輸入下面兩行命令：**
 <font size=4 color="black">` import tkinter `</font>
 <font size=4 color="black">` tkinter._test() `</font>
* **同 Windows 的驗證一樣，在 Python 的解釋命令列中輸入：**
<font size=4 color="black">`import tkinter`</font>
<font size=4 color="black">`tkinter._test()`</font>
 



<font size=6 color="Orange">第一個 Tk 程式</font>
---
**` from tkinter import `**
**`from tkinter import ttk`**

**`root = Tk()`**
**`ttk.Button(root, text="Hello World!").grid()`**
`root.mainloop() `
**將檔案儲存為「hello.py」，在命令提示字元或者 Bash 中輸入：**
`python hello.py`







## <font size=6 color="008F8F">發表評論</font>

:::info
**有任何缺漏?** 發表評論!
:::


###### tags: `Templates` `Documentation`