## :grapes: インストール方法
1.このリポジトリを複製<br>
`$ git clone https://github.com/yumeyuniko/furima-28113.git`

2.インストールしたリポジトリに移動<br>
`$ cd furima-28113`

3.gemをアプリケーションに適用<br>
`$ bundle install`<br>

4.DBの作成&反映<br>
`$ rails db:create`<br>
`$ rails db:migrate`<br>


5.アプリケーションの起動<br>
`$ rails s`<br>
:point_right:`http://localhost:3000`





|入力内容 | 備考 | 
| :--- | :---: | 
| フリマアプリのURL | http://52.196.164.12/ | 
| Basic認証のIDとパスワード| ID:admin  / password:2222 | 
| 出品者用のメールアドレスとパスワード| :e-mail: sample@gmail.com   :key:111aaa | 
| 購入者用のメールアドレスとパスワード| :e-mail: sample1@gmail.com   :key:111aaa | 
|購入用カードの番号・期限・セキュリティコード| カード番号 :4242424242424242 |  
|セキュリティコード|CVC: 123|  
|有効期限|登録時より未来|  

## ■ Summary


## ■ Function

* credit-card registration(PayJP)


## ■ Language
### server-side
* Ruby 2.6.5
* 
### front-end


## ■ Flamework
* Ruby on Rails 6.0.0

## ■ Database
* MySQL 5.6.50

## ■ Infrastructure
* AWS EC2
* AWS S3

## ■ Deploy
* automated deployment by capistrano

[![Image from Gyazo](https://i.gyazo.com/0ccc44629dd5ee466c92ae70cbbdd123.png)](https://gyazo.com/0ccc44629dd5ee466c92ae70cbbdd123)




 ![d390713e26def0c647798de90f3a5dc4](https://gyazo.com/3f34889a9a0d994bff0343c306fb639b.gif)