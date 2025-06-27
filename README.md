# astro-form-document

## ツール概要

OpenAPI SpecificationsでAPIの仕様を定義し、Swagger UIで表示します。

## ディレクトリ構成
```yaml
/openapi.yaml: APIのメイン定義
/index.html: Swagger UIの表示用
```

## Gemini CLIの導入方法

 ```powershell
 # Powershellで実行
  (New-Object Net.WebClient).DownloadFile(
  "https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe",
  "$env:Temp\GoogleCloudSDKInstaller.exe"
  )
  & "$env:Temp\GoogleCloudSDKInstaller.exe"
  # ログイン、プロジェクトの選択を行う
  ```
```cmd
npm install -g firebase-tools
gcloud init
gcloud auth application-default login
setx GOOGLE_CLOUD_PROJECT xxxxxx-xxxxxx
gcloud services enable cloudaicompanion.googleapis.com
npm install -g @google/gemini-cli

```
## Swagger の起動方法


Swagger & OpenAPI
Vercelのフロント＆API
Firebase Authorication & FireStore