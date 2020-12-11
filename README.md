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
| フリマアプリのURL | https://furima-28113.herokuapp.com/ | 
| Basic認証のIDとパスワード| ID:admin  / password:2222 | 
| 出品者用のメールアドレスとパスワード| :e-mail: seller_user@gmail.com   :key:111aaa | 
| 購入者用のメールアドレスとパスワード| :e-mail: buyer_user@gmail.com   :key:111aaa | 
|購入用カードの番号・期限・セキュリティコード| カード番号 :4242424242424242 |  
|セキュリティコード|CVC: 123|  
|有効期限|登録時より未来|  

## ■ Summary
- This is a clone website of Japanese EC site.
- We did agile software development with a team of 4

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

test

test２