# sample_go
Go言語の練習用レポジトリ

## 疑問点

Pythonとはパッケージ管理の方法が少し違うっぽい

go modules: Go言語のプロジェクトにおける依存関係管理システム

go mod: go modulesを操作するためのメインコマンド

go mod init <module-path>: カレントディレクトリにgo.modファイルを作成する

go modulesの中心となるのがgo.modファイル

go get: 指定されたパッケージをダウンロードし，go.modファイルに依存関係として追加する．
