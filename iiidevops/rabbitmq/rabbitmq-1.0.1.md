## 部署開發用 RabbitMQ
- :warning: 此部署僅為測試環境開發階段使用，為單節點配置，如需部署至 Production 環境，請另外修改配置設定, 不要直接使用

## 使用說明

### 啟動自動匯入資料的方式

1. 目前 [RabbitMQ](https://hub.docker.com/_/rabbitmq) 使用 3 的版本，可依需求進行調整。
2. 建置完成後，請從「實證環境」中的服務 rbmq-webui-port 連進入管理網頁介面, 程式所使用的連結資訊請查看使用 rbmq-server-port 的服務連結。

## 資料庫帳號與密碼設定

* `rbmq.username`: 使用者帳號
* `rbmq.password`: 使用者密碼 

#### `rbmq.tag` 可用的版本選擇，若不選擇則預設`rabbitmq:3-management`

