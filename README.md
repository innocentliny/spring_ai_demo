# Spring AI + OpenAPI demo
一個超簡單的使用 Spring AI 串接 OpenAPI 的範例，

## Config
需要先在 `application.yaml` 設定有效的 OpenAI API key。 

## Usage
```shell
curl 'http://localhost:8080/api/chat?message=who%20are%20you'
```
這樣會問 ChatGPT `who are you`。