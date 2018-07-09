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


## Author

[Neo](http://neo.s21.xrea.com/) ([@Neos21](https://twitter.com/Neos21))

- [GitHub - practice-node-uml](https://github.com/Neos21/practice-node-uml)


## Links

- [Neo's World](http://neo.s21.xrea.com/)
- [Corredor](http://neos21.hatenablog.com/)
- [Murga](http://neos21.hatenablog.jp/)
- [El Mylar](http://neos21.hateblo.jp/)
- [Bit-Archer](http://bit-archer.hatenablog.com/)
- [GitHub - Neos21](https://github.com/Neos21/)
