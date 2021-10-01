# Farmosa2021
> Farmosa 為消費者提供更直覺、即時的蔬果查價平台和相
> 關資訊，很輕易的能得知市場行情，再也不用擔心買入不合
> 理的價格和非當季的蔬果

## 功能
• 即時蔬果查價

• 歷史價格查詢

• 當季蔬果推薦

• 發文讚嘆水果

• 喜好水果收藏

## ER model![](https://i.imgur.com/3qjOL9u.png)


## Database建構
使用MySQL做資料庫，並用Node.js (Express)作為後端框架，使用docker-compose整合開發環境。

## 網頁前後端溝通
1. 藉由網頁後端node.js和mySQL作資料庫的讀寫增刪
2. 後端會提供前端API(HTTP request)
3. 只要前端(User)有任何對資料的操作，會藉由request以JSON格式通知後端
4. 後端更新資料

## Screenshot
![](https://i.imgur.com/qc41min.png)
![](https://i.imgur.com/JvYPXBs.png)
![](https://i.imgur.com/pqAJjXT.png)
![](https://i.imgur.com/lK5oWkQ.png)
