# YAML から JSON へ



YAMLドキュメントを貼り付けてJSONに変換します。 マッピングは文字列キーを使用しなければならず、出力はフォーマットされ、コピーまたはダウンロードの準備ができています。





## 使い方



1. 文字列マッピングキーでYAMLドキュメントを1つ貼り付けます。
2. JSONに変換。
3. 結果を検査、コピーまたはダウンロードしてください。







## 例



### 入力



```
name: ToolPony
ready: true
```



### 期待される結果



```
{
  "name": "ToolPony",
  "ready": true
}
```







## 試してみる

[ツール全体を開く · YAML から JSON へ](<https://toolpony.com/ja/tools/yaml-to-json/>)





## 注意点



JSON が表現できない複数のドキュメント、カスタムタグ、サイクリックエイリアス、および値が拒否されます。 値を引用すると、論理値や数字ではなく文字列を意味します。







## 制限



最大1MBまで。 カスタムタグ、複数のドキュメント、非文字列キー、過剰なエイリアス、サイクリック構造、およびJSONが保持できない値は拒否されます。





**計算・処理の参考資料** [YAML 1.2.2](<https://yaml.org/spec/1.2.2/>) · [IETF · RFC 8259 (JSON)](<https://www.rfc-editor.org/rfc/rfc8259>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fyaml-to-json%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/yaml-to-json/)
