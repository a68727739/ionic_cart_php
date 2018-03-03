    
```
    step01 建立資料庫 並修改 conn.php 相關資料庫參數值
    step02 進入 ionic-shopping-cart 資料夾 進入 SQL資料夾 將 products.sql 、 users.sql 匯入資料庫
           或使用 資料庫檔案ionic_cart.sql
    step03 進入 ionic-shopping-cart 資料夾 npm install
    step04 修改 \ionic-shopping-cart\www\js\ 下的 
           controllers.js 與 services.js  
           將其中 http://localhost/ionic-shopping_php/  
           改成自己對應的server域名
    step04 運行
            $ ionic cordova platform add ios
            $ ionic cordova platform add android
    step05 ionic serve 或  ionic cordova run android
```
![image](https://github.com/a68727739/ionic_cart_php/blob/master/demo01.gif)
