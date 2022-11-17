# HTTPのお話 2022-11-17

- httpとは通信のルールであり、request, responseをクライアント・サーバー間で行われる
- httpはrequest,responseの仕様を決めているに過ぎない
- httpではいろいろなファイルを送れる
- webを表示する際に RequestUrlに照合するデータをサーバーにリクエストする
- html,css,js をhttpでやり取りする。 jsonmもやり取りできる
- apiのresponseがjsonなのはweb上で動くjsで扱いやすいから
- サーバーサイド言語はリクエストの中身の参照しかできない、そしてレスポンスを返す
- フロントエンドはリクエストを送る。
- リクエストの欲しい情報を考えることができればあとはググるだけ
- レスポンスはhttpの仕様に従ってレスポンスを作るだけ


## request

- method, headerが存在

## response
- status code,headerが存在






参考　: https://triple-underscore.github.io/RFC7231-ja.html

written by Eiki Watanabe
