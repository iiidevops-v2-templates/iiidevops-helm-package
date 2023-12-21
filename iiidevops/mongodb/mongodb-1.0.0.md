# (注意)登入權限差異

* 若以使用者自行設定的帳號密碼登入時，僅可看到使用者要求的資料庫
* 備份資料庫若含獨立的`database`則需登入root帳戶才可看到
* 若僅含`database`內的資料，將會預設匯入到使用者要求建立的資料庫名稱內

## 資料庫帳號與密碼設定

* `db.username`: 使用者帳號
* `db.password`: 使用者密碼(亦為root密碼)


## 資料庫統一採用bitnami
* [mongodb](https://hub.docker.com/r/bitnami/mongodb)
* [mongo-express](https://hub.docker.com/_/mongo-express)

## 版本說明

* [按照原始yaml檔案為基礎做轉為chart版本 非標準](0.1.0)
* [改進原始版本無法判別資料庫啟動狀況](0.1.1)