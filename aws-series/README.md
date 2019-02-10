#### m09:mariaDB  
    * 用dockerCompose，製作一個具有jupyter 與 mariaDB 兩個Container的環境  
    * 指定 jupyter的源碼資料夾保存位置 、 mariaDB的資料保存位置 回本地端  
    * 資料庫域名須為 cc104.rds.local  
    * jupyter環境需奠基在dockerfile之上  
    * 使用gitignore技術，將mariaDB的資料夾進行忽略  

  ---

#### m10:mysql  
    * jupyter 開啟時，已經自動安裝PyMySQL套件  
    * 開啟一個rds-example.ipynb  
    * 嘗試使用PyMySQL套件連結至mysql  
    * 創建資料庫，資料表 
    * 插入資料  
    * 查詢資料
  ---

#### m11:dynamodb  
    * 在docker-compose.yml檔內追加一個dynamodb container  
    * dynamodb的域名須為 cc104.dynamodb.local  
    * jupyter 開啟時，已經自動安裝boto3套件  
    * 開啟一個dynamo-example.ipynb   
    * 在裡面嘗試使用boto3套件連結至dynamodb進行  
    * 創建資料庫，資料表，插入資料，查詢資料，刪除資料  
  ---

#### m12:sqs
    * 在docker-compose.yml檔內  
    * 再追加一個sqs container  
    * sqs的域名須為 cc104.sqs.local  
    * 開啟一個sqs-example.ipynb  
    * 在裡面嘗試使用boto3套件連結至sqs進行  
    * 創建queue，丟message進入queue，從queue拉出message，刪除在queue裡的message  
  ---

#### m13:s3
    * 在docker-compose.yml檔內追加一個s3 container  
    * sqs的域名須為 cc104.s3.local  
    * 開啟一個s3-example.ipynb，在裡面嘗試使用boto3套件連結至s3進行 創建bucket  
      * put data into bucket  
      * get data from bucket  
      * delete data from bucket  
      * list all bucket (fask環境無此功能)  
  ---
