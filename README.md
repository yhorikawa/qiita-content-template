# qiita-content-tamplate

https://github.com/yhorikawa/qiita-content で使っているテンプレートです

## 使い方
devContainerやcodespacesで使うことができます

## vscode devContainerで使う場合
credentials.jsonを作成してください
```credentials.json
{
  "default": "qiita",
  "credentials": [
    {
      "name": "qiita",
      "accessToken": "発行したトークン"
    }
  ]
}
```

`cmd + shift + p`を押して`Dev Containers: Reopen in Container`を選択し起動します
