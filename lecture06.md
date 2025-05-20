# 第6回課題


## CloudTrailのイベント

### イベント名
* StopInstances(インスタンス停止)
![](image01.jpg)
### イベント時間
* 2025年5月15日 19:25:46
### ユーザー名
* nk29
### 参照されたリソース（対象インスタンス）
* i-0bbe172f4bc82381c
### イベントレコード
![](image02.jpg)

## CloudWatchアラームを使ってALBの設定

### アラームを作成
メトリクス名(UnhealthyStateRouting)
* Railsアプリケーションが使えない時:アラーム状態のステータス
![](image03.jpg)
* Railsアプリケーションが使える時:OKのステータス
![](image04.jpg)
### Amazon SNSでメール通知設定
* 「ALARM」
![](image05.jpg)
* 「OK」
![](image06.jpg)

## AWS利用料の見積もり作成
https://calculator.aws/#/estimate?id=3ae0c1840420e9e5b7f842182cae6f4473dfac01

### 今月までのAWSの利用料
* 合計コスト $106.01
* 使ってないVPCやEC2インスタンスは削除したり、Elastic IPを解放するなど対策していかないといけないと思った。
![](image07.jpg)
![](image08.jpg)













