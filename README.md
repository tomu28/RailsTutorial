# １章
## herokuで変更し、起動コマンド
    git commit -a -m "Update Gemfile for Heroku"
    git push heroku master
    heroku open

## 1章まとめ
- Ruby on Railsとは、Web開発のためのフレームワークであり、Rubyプログラミング言語によって記述されている。
- 事前設定済みのクラウド環境を利用することで、Railsのインストール、アプリケーションの生成、生成されたファイルの編集を簡単に行うことができる。
- Railsにはrailsという名前のコマンドラインコマンドがあり、rails newで新しいアプリケーションを生成したり、rails serverでローカルサーバーを実行したりできる。
- コントローラのアクションを追加したり、ルートルーティングを変更したりするだけで- -「hello, world」アプリケーションを作成できる。
- Gitによるバージョン管理を導入し、Bitbucketの非公開リポジトリにプッシュする理由は、データの喪失を防止し、他の開発者との共同作業を行えるようにするため。
- 作成したアプリケーションをHerokuの本番環境にデプロイした。
<https://railstutorial.jp/chapters/beginning?version=5.1#cha-beginning>より
