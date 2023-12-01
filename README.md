# student-management-system-backend
A student management system backend developing pratical project using **flask**. 2023/05

# 概要
Flaskを用いた開発した教務システムのバックエンド部分である。実行ができるが、フロントエンドがないため操作が少し困難である。  

開発＆テスト環境：Venv on local PC、AWS Cloud9（両方の環境にもテストを実行した）  

主な機能：
* ログイン
* 学生、教師、専攻、科目等の検索、閲覧、追加、削除
* 学生の授業科目選択と削除
  
主な構成部分：
* models: 各部分（学生、教師、科目、クラス…）のモデルの設定
* service: appにあるシステムの機能の関数の具体的な設定
* app.py: システムの機能定義

# 実行手順
* ダウンロードしてからzipファイルを解凍する
* ターミナルでpython -m venv venv でVenv環境を作り、.\venv\Scripts\activate でVenv環境を起動する。
* pip install flaskでFlask をインストール。Flask 以外にも下記のパッケージのインストールが必要で、pip install を使ってインストールすること。
  * [SQLAlchemy](https://www.sqlalchemy.org/)
  * [simplejson](https://pypi.org/project/simplejson/)
  * [Cors](https://flask-cors.readthedocs.io/en/latest/)
* ターミナルでset FLASK_APP=app.pyで実行のmainファイルを指定する。
* ターミナルでflask runを入力し、アプリケーションを起動する。
