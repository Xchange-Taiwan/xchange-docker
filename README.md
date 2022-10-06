###XChange Container Environment
---
####DynamoDB Setup
- Download package from [here](https://docs.aws.amazon.com/zh_tw/amazondynamodb/latest/developerguide/DynamoDBLocal.DownloadingAndRunning.html).
- Unzip the package `dynamodb_local_latest.tar.gz` 
- Move `dynamodb_local_latest` to current directory, and create another folder `data` in it.
- Install DynamoDB GUI. exec the cmd: 
  - `npm i dynamodb-admin`
<br>

####ElasticSearch Setup
- Description...
<br>

####Launch Docker
- Execute the following cmd:
  - `docker-compose up -d`
  - `dynamodb-admin`
- Open `http://localhost:8001/`
