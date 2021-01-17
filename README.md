## rubyのバージョン管理に関して

以下で起動できる
```
ruby 2.6.3
rails 5.2.3
```

設定方法
```
// 所持しているバージョン確認
rbenv versions
// インストール
rbenv install 2.6.3
// バージョン切替※loacl指定すると.ruby-versionが作成され、ディレクトリ単位で管理できる
rbenv local 2.6.3
// プロジェクト以下にインストール※バージョン単位でパッケージが切替るので指定しなくてもいいかも。
bundle install --path vendor/bundle
```
⭐️rubyのバージョンを切り替えると関連するbundlerやrailsも切り替わるので注意！！
