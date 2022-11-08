# smartDorm
###############
<h3>🟫 使用的材料</h3>
1. 超音波距離感測器 HC-SR04<br>
2. 繼電器模組<br>
3. Arduino UNO<br>
4. PC<br>
<br>
###############<br>
<br>
💡💡💡💡💡💡💡💡💡💡💡💡💡💡💡
<br>
<h3>安裝一個自動化控制宿舍桌上的檯燈</h3>
<h4>這是一個我新發現的物聯網實現方法之一<br>
也可以說是一種帶有 SoC 軟硬體整合概念的小專題<br>
可以透過Arduino與電腦內的Python透過序列阜進行溝通<br>
</h4>

========================================<br>
🟩 Arduino負責硬體：<br>
1. 持續讀取超音波感測器資料<br>
2. 持續等待使否有指令需控制繼電器<br>

========================================<br>
🟥 電腦Python負責軟體：<br>
1. 判斷式都寫在這邊<br>
2. 整合拿到的資料，做出控制的決策<br>

========================================<br>
🟧 雲端Google App Script 負責 API端口：<br>
1. 接收資料串入做判斷 <br>
2. 加上 Time code 後將資料輸出至Google sheet <br>
3. 透過 Google 自家生態鏈利用 GAS 排版 Google Sheet <br>

![image](https://user-images.githubusercontent.com/52557611/200508579-7826d72e-7090-452c-9984-d16858ba6eb3.png)
![image](https://user-images.githubusercontent.com/52557611/200508630-db91f790-70d0-4f37-9a2f-77011b82b5fb.png)
![image](https://user-images.githubusercontent.com/52557611/200508716-a0b63234-7bbd-4126-899f-baeafdf9d480.png)
