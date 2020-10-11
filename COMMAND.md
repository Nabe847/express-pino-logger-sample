# express のデバッグログをコンソールに出力させる

(DEBUG に express の名前空間を追加する)

-   参考：https://expressjs.com/en/guide/debugging.html
-   `set DEBUG=express:*`

# コンソールへ出力するログを pino-pretty で成型する

-   `node index.js | "./node_modules/.bin/pino-pretty"`
