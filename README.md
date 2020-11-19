# Practice Node.js UML : practice-node-uml

Node.js 環境で UML を描く素振りリポジトリ。


## Mermaid.js : `mermaid.cli`

- Install

```sh
$ npm install mermaid.cli --save
```

- `package.json`

```json
{
  "scripts": {
    "mmdc": "mmdc",
    "generate-mermaid": "mmdc --input example-mermaid.md --output output-mermaid.png"
  }
}
```

- `--input` : `-i`
- `--output` : `-o`


## Plant UML : `node-plantuml`

- Install

```sh
$ npm install node-plantuml --save
```

- `package.json`

```json
{
  "scripts": {
    "puml": "puml",
    "generate-plantuml": "puml generate --png --output output-plantuml.png example-plantuml.md"
  }
}
```

インプットとなるファイル (`example-plantuml.md`) は Shift-JIS エンコーディングにしておかないと、日本語のレンダリング結果が文字化けしてしまう。


## Bibliography

- <https://www.npmjs.com/package/node-plantuml#example>
- <https://ryuta46.com/516>


## Links

- [Neo's World](https://neos21.net/)
