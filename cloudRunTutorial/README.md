## CloudStorage の画像処理のチュートリアル

[URL](https://cloud.google.com/run/docs/tutorials/image-processing#run_imageproc_handler_analyze-python)

### overview

画像処理アプリを CloudRun でデプロイ、pubsub トピックにサブスクリプションを作成

GCS への画像アップロードをトリガとして、pubsub トピックにメッセージを publish

不適切なコンテンツはぼかして別のバケットへコピーする
