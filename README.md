# jruby-mssql-rails-app

JRuby と SQL Server を利用した Rails アプリケーションです。

- Docker Compose と Dev Container を利用しています。
- JRuby には [jruby:9.4.8.0-jdk11](https://hub.docker.com/_/jruby) のイメージを利用しています。
- SQL Server には [mcr.microsoft.com/mssql/server:2022-latest](https://hub.docker.com/r/microsoft/mssql-server) のイメージを利用しています。
- Rails を JRuby と SQL Server で動作させるために [activerecord-jdbc-alt-adapter](https://rubygems.org/gems/activerecord-jdbc-alt-adapter) の gem を利用しています。
- Scaffold を生成して CRUD 操作ができるところまで実装しています。
