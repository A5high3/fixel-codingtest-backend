# fixel-codingtest-backend

json-serverを用いたモックサーバー
## ショートコマンド
- npm run db-start

4000番ポートでモックサーバーを立ち上げる。
3000番でフロントを立ち上げるため、ブッキングしないように4000番を指定

## json-serverコマンド

npx json-server --watch ${DBとして用いるjsonファイル} --port ${localで立ち上げるポート番号}

