# 第5回課題


## 組み込みサーバー（puma）のみでのRailsアプリケーション動作確認
* pumaの状態
![](image1.png)
* webブラウザでの確認
![](image2.png)

## 組み込みサーバ-(puma)とUnix Socketを使ったRailsアプリの動作確認
* pumaの状態
![](image3.png)
* curlでの確認
![](image4.png)

## Nginxのみでの起動確認
* Nginxの状態
![](image5.png)
* Nginx画面が表示されることを確認
![](image6.png)

## 組み込みサーバー（puma）とNginxを使ったRailsアプリケーション動作確認
* webブラウザでの確認
![](image7.png)

## ALBを追加して動作確認
* webブラウザでの確認
![](image8.png)

## S3を追加
* 画像が保存されるようにS3を設定、webブラウザで画像を登録
![](image9.png)
* S3に画像が保存されたことを確認
![](image10.png)

## 構成図
![](image11.png)