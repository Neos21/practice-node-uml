/' 読み込むファイルは Shift-JIS エンコードを指定しておくと日本語も文字化けせず描画できる '/

actor ボブ
participant Alice

ボブ->Alice : こんにちは
activate Alice

Alice-->ボブ : Hello
deactivate Alice
