# React の勉強メモ

いまどきの JS プログラマのための Node.js と React アプリケーション開発テクニック
JavaScript Standard Style > Rules  
https://standardjs.com/rules.html で JS のコーディング規約について決められている

規約

- セミコロンを記述しない
- ==よりも===
- インデントはスペース 2 こ
- ダブルクォートよりもシングルクォート

知識

### 入出力処理が連続して行われる → コールバック関数が連続出現、ネストも深くなり可読性が落ちる

解決法

- Promise を使う
- async await を使う
