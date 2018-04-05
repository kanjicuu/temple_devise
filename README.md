# README

ログイン機能、そしてmaterialize導入し、使いまわすことの多い基本的なテンプレートを作成した。

* 追加したgemfile

gem 'materialize-sass', '~> 1.0.0.beta'
gem "devise", "~> 4.2"
gem 'material_icons'


* DataBase creation
User model(deviseを使用。)
email
password

* flashメッセージ
materializeのtoasterに適用。


* registration_controller を新たに作成。
これにより、passwordの入力なしで、user情報が更新できる。


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
