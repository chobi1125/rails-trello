## rubyのバージョン管理に関して

以下で起動できる
```
ruby 2.6.3
rails 5.2.3
```

```terminal
// 所持しているバージョン確認
rbenv versions
// インストール
rbenv install 2.6.3
// バージョン切替※loacl指定すると.ruby-versionが作成され、ディレクトリ単位で管理できる
rbenv local 2.6.3

⭐️rubyのバージョンを切り替えると関連するbundlerやrailsも切り替わるので注意！！

// プロジェクト以下に依存パッケージをインストール
bundle install --path vendor/bundle

```
