## API 文档  

### 概述  
本项目提供了一套强大且灵活的 API，使用户能够轻松地与“aitest”系统进行交互。API 采用 RESTful 风格，使用 JSON 格式的数据交换，设计简洁且易于使用。  

### 端点总览  
以下是主要 API 端点的概览：  

- `GET /api/v1/models`：获取可用模型的列表。  
- `POST /api/v1/models`：上传新的模型。  
- `GET /api/v1/models/{id}`：获取指定模型的详细信息。  
- `DELETE /api/v1/models/{id}`：删除指定的模型。  
- `POST /api/v1/tests`：创建新的测试实例。  
- `GET /api/v1/tests/{id}`：获取指定测试实例的结果。  

### 身份验证  
所有 API 请求均需进行身份验证，以确保安全性。请使用 Bearer Token 进行授权，将其添加到请求头中
