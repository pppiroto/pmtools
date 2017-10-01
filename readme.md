# Project Management Tools

## Memo
https://cloud.google.com/appengine/docs/standard/python/quickstart?hl=ja#before-you-begin
### run local server
> cd src
> py -2 %gcp sdk bin path%/dev_appserver.py app.yaml
###
> cd src
> gcloud app deploy

### Complex Indexies
*https://cloud.google.com/datastore/docs/concepts/indexes?hl=ja&_ga=2.175481316.-798702131.1506086034
インデックス設定ファイルの変更が完了したら、コマンドを実行してインデックスの使用を開始します
> gcloud datastore create-indexes index.yaml