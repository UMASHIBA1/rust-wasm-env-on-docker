# rust wasm env on docker

Rust で書いた WebAssembly プロジェクトを動かせる Docker 環境です。

`docker-build.ps1`のスクリプトを実行した後、`docker-run.ps1`のスクリプトを実行してください。  
app ディレクトリ内が共有された状態で rust wasm 実行環境に入ります。

実行環境は[こちら](https://rustwasm.github.io/docs/book/game-of-life/setup.html)のセットアップが完了した状態になっています
