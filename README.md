### QR2PIC:  
  ---
    * 用docker-compose建立jupyter環境  
    * 安裝qrcode,Pillow套件  
    * 輸入網址或文字後，可轉為QR圖像  

  ---

### m04:  
  ---
    * 用docker-compose建立jupyter環境  
    * upyter下開啟lab1_json_operate.ipynb  
    * 創建一個檔案，裡面塞入一個json object  
    * object裡面需要有四個欄位，分別對應到 string, number, object, array  
    * 讀取該檔案做操作，將四個欄位進行內容修改，存回原檔案  

  ---

### m05:  
  ---
    * 用docker-compose建立jupyter環境  
    * 使用python的request模組去訪問https://jsonplaceholder.typicode.com/users  
    * 取得第2,3,4,5 筆資料  
    * 偵測當時日期，轉作檔名  
    * 將2,3,4,5 筆資料內容寫入檔案中  

  ---

### m06:  
  ---
    * FlaskServer入門 - 端口初體驗  
    * 撰寫一個Flask Server  
    * 設計一個端口  
    * 用戶能對此端口用get方法訪問  
    * 傳回{"userId":1,"userName":"xiaoming"}  

  ---

### m07:  
  ---
    * FlaskServer入門2 - QueryString  
    * 撰寫一個Flask Server  
    * 為user設計一個端口  
    * 用戶能對此端口用GET方法訪問,並且挾帶query string(id=xxx)  
    * 若用戶傳入 id=123，則傳回json格式{"userId":123}  

  ---

### m08:  
  ---
    * FlaskServer入門2 - QueryString  
    * 撰寫一個Flask Server  
    * 為user設計一個端口  
    * 用戶能對此端口用POST方法訪問，挾帶任意json body  
    * 將此body轉存成檔案，存在伺服器上，並將此檔案上傳至iii-tutorial-v2桶內的student{座號}資料夾下  

  ---
