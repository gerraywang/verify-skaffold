# verify-skaffold

##　検証内容
すでにある環境にサービスを追加して、しかも既存環境のCICDパイプラインを流用できない場合、Skaffoldを使って、Manifestを含めて自動デプロイでるように、軽いCICDパイプライン構築方法を模索する。

## 手順
1. GKE
2. Cloud Deployを作成して、GKEと紐づけ
3. Cloud Buildを作成し、cloudbuild.yamlと紐づけ
