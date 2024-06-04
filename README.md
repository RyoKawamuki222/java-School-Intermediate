1 概要
本アプリケーションはユーザー情報の一覧と新規登録ができるシステムです。

・ユーザー情報画面一覧では、登録した情報を確認できます。
http://localhost:8080/user/list
![スクリーンショット (24)](https://github.com/RyoKawamuki222/java-School-Intermediate/assets/171565634/1b3ec2aa-4272-4a36-80d9-ccb01299ebc0)

・「新規登録はこちら」をクリックすると、ユーザーの新規登録ができます。
http://localhost:8080/user/add
![スクリーンショット (25)](https://github.com/RyoKawamuki222/java-School-Intermediate/assets/171565634/abd4dd98-7459-4001-bbab-9c90f7e0de29)

主要機能
ユーザー情報一覧画面：すべてのユーザー情報を一覧表示します。
ユーザー新規登録画面：ユーザー名、パスワード、メールアドレスを入力して登録します。パスワードは暗号化されて保存されます。

2 使用技術
・java ver 21.0.1
・springframework.boot version　3.2.5
・Gradle
・Spring Web
・Thymeleaf
・Lomback
・PostgreSQL Driver
・MySQL
・Mybatis
・Docker/Docker-compose
・A5:SQL Mk-2 SQL Client/ER Diagram tool
・VScode

3 構成図
ユーザー新規登録の流れ

・UserRequest:ユーザー新規登録画面の入力処理
・UserController:各画面表示及び入出力処理など、リクエストに対応する処理を呼び出す
・UserRepository:DBにアクセスする処理
・UserMapper:DBにアクセスする処理、知っ祭にアクセスするコードが書かれている

javaの中級研修で学んだことを、実務で使用するような開発環境で実際に実装～動作確認を行いました。
