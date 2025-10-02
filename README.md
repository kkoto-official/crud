# Webアプリケーション　テンプレ

## 環境構築
Gitからリポジトリをダウンロード
``` cmd
git clone --recurse-submodules https://github.com/kkoto-official/crud.git
```

### バックエンド
`./crud-back/.env`を編集する<br>
主にフロントにアクセスするIPアドレスを編集する


### フロントエンド
`./crud-front/.env.local`を編集する<br>
主にバックにアクセスするIPアドレスを編集する

## 更新作業
``` cmd
git pull --recurse-submodules
```
