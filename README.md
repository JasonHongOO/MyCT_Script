# MyCT_Script

以上為本人經淺層且簡單的遊戲逆向工程寫出的AOB腳本，為了實現 Code Injection 以修改遊戲機制或獲取的遊戲物件

CT 腳本為 Cheat Engine 使用的程式，之所以將AOB腳本包成CT腳本是為了方便不懂程式的人也可以輕鬆使用，同時也達成開放 Source Code 的目的，讓有志人士能在之後遊戲更新時，方便更新腳本。

# CT腳本範例展示

![image](https://github.com/JasonHongOO/MyCT_Script/blob/main/Images/1.PNG)

# 使用方式

#### 打開 Cheat Engine 並選擇遊戲進程

![image](https://github.com/JasonHongOO/MyCT_Script/blob/main/Images/2.PNG)

#### 點擊  Value 顯示為 script 的那一列最左側的方框，就能成功 Injection 腳本到遊戲程式中

###### (原先)

![image](https://github.com/JasonHongOO/MyCT_Script/blob/main/Images/3.PNG)

###### (之後)

![image](https://github.com/JasonHongOO/MyCT_Script/blob/main/Images/4.PNG)

#### 如有特殊需求，想要修改腳本內容只要雙擊 script 的字串，就能修改腳本的組合語言

![image](https://github.com/JasonHongOO/MyCT_Script/blob/main/Images/5.PNG)

# 提醒

有些遊戲會偵測電腦是否有開啟 Cheat Engine，如果有類似狀況發生，需先完整開啟遊戲後，在開啟 Cheat Engine。

# 使用的相關逆向工程軟體
###### 一般軟體
- Dnspy
- IDA Pro
- Cheat Engine

###### 開源軟體
- minhook (https://github.com/TsudaKageyu/minhook)
- Il2CppDumper-GUI (https://github.com/AndnixSH/Il2CppDumper-GUI)
- ProcessHacker (https://github.com/PKRoma/ProcessHacker)
