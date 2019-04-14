# myproj
template go project

```
myproj/
  ├── Makefile          # ビルド定義の他タスクランナー的にも利用
  ├── myproj.go         # ソースコード
  ├── myproj_test.go    # テストコード
  ├── type1.go          # typeを定義しているものはファイルを分けても良い
  └── type1_test.go
  ├── logger/           # 必要な場合サブディレクトリにサブパッケージを配置する
  │   └── logger.go     # package logger
  ├── cmd/              # 実行バイナリ用のソースが配置される
  │   └── myproj/       # package main
  │       └── main.go
  ├── internal/         # 外部から利用されたくないパッケージを配置
  ├── testdata/         # fixtureなどのテストデータを配置
  ├── _tools/           # Go以外のシェルスクリプトを配置
```
