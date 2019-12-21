# WebSiteLab
系統需求<br>
-----------
1. Python 3.0以上
2. Django
3. 若Windows系統執行有異狀，檢查sqliteDB.py，將/db.sqlite3 改為 \\db.sqlite3

安裝步驟
------------
請先下載ＧitHub上所有檔案，於檔案位置開啟終端機，並執行 python manage.py migrate
<img src="https://github.com/Connie8763/WebSiteLab/blob/master/migrate.jpg"><br>
接著執行 python manage.py runserver 開啟server
<img src="https://github.com/Connie8763/WebSiteLab/blob/master/runserver.jpg"><br>
<br>
完成後開啟瀏覽器·並輸入 http://127.0.0.1:8000/login 即可進入 “登入介面”，如果登入失敗超過5次，等待30秒後才能繼續登入（第六次等待30^2秒）
<img src="https://github.com/Connie8763/WebSiteLab/blob/master/login.jpg"><br>
如要註冊，點擊頁面中超連結
<img src="https://github.com/Connie8763/WebSiteLab/blob/master/regist.jpg"><br>
註冊並登入後，可以進入房地產頁面，此頁面可新增資料至sqlite，此外，admin權限者可以刪除，查詢，user及guest的資料及帳號，user能查詢本身與guest資料，guest只能查詢自己．
<img src="https://github.com/Connie8763/WebSiteLab/blob/master/manage.jpg"><br>
