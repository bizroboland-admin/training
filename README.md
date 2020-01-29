# 研修用サイト

## ログイン画面
* [ログイン画面](https://goodlife-training-site.firebaseapp.com/login/)
## 映画サイト
1. [映画サイト 1](https://goodlife-training-site.firebaseapp.com/movie/1/)
1. [映画サイト 2](https://goodlife-training-site.firebaseapp.com/movie/2/)
1. [映画サイト 3](https://goodlife-training-site.firebaseapp.com/movie/3/)
1. [映画サイト 4](https://goodlife-training-site.firebaseapp.com/movie/4/)
## 株価サイト
1. [株価サイト 1](https://goodlife-training-site.firebaseapp.com/finance/1/)
1. [株価サイト 2](https://goodlife-training-site.firebaseapp.com/finance/2/)
1. [株価サイト 3](https://goodlife-training-site.firebaseapp.com/finance/3/)
1. [株価サイト 4](https://goodlife-training-site.firebaseapp.com/finance/4/)

## Github
* git init 
  * Reinitialized existing Git repository in C:/_source/TrainingSite/.git/
* edit .gitignore
* ローカルコミット
* git remote add origin https://github.com/bizroboland-admin/training.git
* git push -u origin master

## Hosting
* firebase init
* firebase use goodlife-training-site
* firebase deploy

## ローカルでテストしてサイトにデプロイする
* firebase serve --only hosting
## 
* firebase serve
* firebase serve --only functions,hosting
* firebase serve --only functions

* firebase hosting:disable   : 削除