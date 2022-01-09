# sap-functional-location-sql
sap-functional-location-sql は、主にエッジアプリケーションにおいて、SAPと連携された 機能場所データ を保存するSQLテーブルを作成するためのレポジトリです。  
sap-functional-location-sql は、そのままクラウド環境におけるアプリケーションにも、適用可能です。  

## 前提条件  
sap-functional-location-sql は、SQL の SAP とのデータ連携にあたり、オンプレミス版である（＝クラウド版ではない）SAPS4HANA API の利用を前提としています。クラウド版APIを利用する場合は、ご注意ください。  
https://api.sap.com/api/OP_API_FUNCTIONALLOCATION/overview  
本レポジトリ の sql設定ファイルの内容は、上記URL の API 仕様を前提としています。  

## sqlの設定ファイル
sap-functional-location-sql には、sqlの設定ファイルとして、sqlの設定ファイルとして以下のsqlファイルが含まれています。  

* sap-functional-location-sql-header-data.sql（SAP 機能場所 - ヘッダ）

## MySQLのセットアップ / Kubernetesの設定 / SQLテーブルの作成方法
MySQLのセットアップ / Kubernetesの設定 / 具体的なSQLテーブルの作成方法、については、[mysql-kube](https://github.com/latonaio/mysql-kube)を参照ください。