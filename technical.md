# 中央大学ポータルCplus テクニカルドキュメント

CPlusの技術仕様についてまとめます。

## 技術選定

```eval_rst
=================   ============================================
ID                  採用
=================   ============================================
Language            Ruby 3.0.0
Flameworks          Rails 6.1.3.1
UI                  Bulma 0.9.2(改造あり)
RDB                 PostgreSQL(詳細はconfig/database.ymlを参照)
CI                  TravisCI
Release Platform    Heroku（予定）
=================   ============================================
```

## インストールとデプロイ

インストールとデプロイは一般的なRailsアプリケーション（DB:Postgres）としてデプロイしてください。特に、HerokuではPostgresの配置以外、特に設定を施すことなくデプロイが可能なはずです。

## API

APIは将来的な公開を目指していますが、現在開発中です。REST API形式で提供され、JWTによって認証を通過していれば適切な権限の元閲覧できるはずです。

## その他問い合わせ先

開発チームの[GitHub](https://github.com/mizphses/cplus)でIssueを投げるか、サポートページにあるフォーム、もしくは[開発代表者のメール fuminori@mizphses.com](mailto:fuminori@mizphses.com) にお問い合わせください。
