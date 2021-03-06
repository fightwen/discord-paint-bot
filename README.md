# Discord Bot

這是"繪畫下午茶"伺服器的機器人，名為"下午茶秘書"。
<br>為了希望有人交流技術面的東西，因此開源了程式碼，**請不要把我的機器人token拿去使用**，不然我的機器人會失效。
<br>想做機器人請到Discord官網自己申請一組機器人token，感謝。

- ``繪畫下午茶 伺服器``是一個給繁體中文圈喜歡動畫、漫畫，以及喜歡畫圖的朋友一個交流的Discord群組。
  <br>目前約二十幾人，最多人在線上估計十一人。
  
- ``下午茶秘書 Bot``是為了畫友客製化的機器人，致力於鼓勵畫友練習畫更多圖，產生的各式各樣的功能。

- 更新日期：2017/10/05 
  > 目前只有許願池的功能，陸續會在增加其他的，如果有靈感的話XD

![](https://github.com/fightwen/dc-bot/blob/master/img/who.png)
  
  
## 許願池
- 因畫友皆希望有點圖活動，點圖意旨 A畫友 指定 B畫友 一個畫圖主題，進而挑戰不一樣的畫圖主題，跳脫自己擅長畫的舒適圈。如何讓大家更積極參與點圖活動，變成群主(我)需要思考的問題。

- 遊戲規則(程式構想)
  > 1.每天只有一個人可以點圖 (使用``i!hope 畫圖主題``一次)，例如：``i!hope 中秋節賀圖``
  >  - 限點圖頻道，其他頻道機器人會提醒你走錯頻道
  >  - 機器人會隨機抓一個伺服器有上線狀態的成員(除了點圖者)，當作被點圖的對象
  >  - 如果非滿一天再使用點圖使令，機器人會提醒你下次可以點圖的時間
  
  > 2.畫好圖後 (``i!done 圖片網址/圖片附件``)，例如：``i!done https://images.xxxxxx.jpg``
  >  - 限點圖頻道，其他頻道機器人會提醒你走錯頻道
  >  - 機器人會提醒隨機被點到的成員，他獲得了一分鐘內一次換暱稱顏色的機會
  >  - 獲得機會的人輸入``i!idcolor @顏色代碼``，機器人會幫他暱稱換他選擇顏色代碼色
  >  - 非點到的成員，也可以使用此指令，但獲得換暱稱顏色的機率是隨機(目前設定為十分之一，意思可能要畫十張圖並使用此指令十次才有機會)
  >  - 使用``i!idcolor x`` 機器人會清除你點圖設定的暱稱顏色 
  
 - 程式技術點
   > 1.使用Python3開發 - 人生苦短，Python簡潔
   
   > 2.使用heroku部屬 - 免費穩定，機器人隨時在線服務
   
   > 3.使用Git版本控管 - 如果寫錯回朔容易，釋出更多版本時好管理
   
   > 4.使用Linux環境 - 指令操作單一快速，不用學太多圖形畫界面的操作
   
   > 5.Discord英文文件、英文技術討論區 - 基本上就是練英文...完全沒有中文可以看，中文圈使用Discord當通訊軟體非常稀少!
   
 ![](https://github.com/fightwen/dc-bot/blob/master/img/help.png)
 
 ``顯示機器人所有功能``
 
 ![](https://github.com/fightwen/dc-bot/blob/master/img/rule.png)
 
``輸入i!rule 機器人私訊你遊戲規則``

 ![](https://github.com/fightwen/dc-bot/blob/master/img/hope.png)

``輸入i!hope 主題 機器人會先刪除你的指令並發出隨機成員點圖的訊息，再一次指令則提醒下次點圖時間``

 ![](https://github.com/fightwen/dc-bot/blob/master/img/done.png)
 
 ![](https://github.com/fightwen/dc-bot/blob/master/img/idcolor.png)

``被點圖者可換暱稱顏色(保護當事人故模糊處理)``

![](https://github.com/fightwen/dc-bot/blob/master/img/error_channel.png)

``錯誤的頻道提醒``


