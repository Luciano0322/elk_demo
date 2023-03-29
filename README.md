## Docker-compose elk 範例
1. elk 於資料夾下面下：
```
docker compose up -d
```
2. mac/linex 環境下確保 setup 資料架下的 bash 權限有開。
3. 預設的 user:pwd = elastic:changeme
4. py-loggin 裡面為發送 log 到 elastic 的方式，如果是 java 的話會有相關套件去做實作  
5. elk_cust 為搭配 apm-server 的版本，環境起來後只需要將掛載 apm agent 的 server 運行就好了。  