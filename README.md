# graduation-thesis

卒業論文用のレポジトリです。


## セットアップ

1. VSCodeとDocker Desktopをインストール
2. VSCodeに[Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)拡張機能をインストール
3. このリポジトリをクローン
4. VSCodeでフォルダを開き、「Reopen in Container」を選択

これにより、LaTeX執筆に必要な環境が自動的に構築されます。

## Boxへの自動アップリロード

mainブランチの更新があるとPDFがBoxに自動アップロードされます。

## 文章校正

TextLintによる文章校正が利用可能です。  
また、latexindentとlatexworkshopにより保存時に自動的にLaTeXのフォーマットが整えられます。

### ローカルでの実行

下記コマンドでローカルで文章校正が実行できます。

```bash
npm install # 初回のみ
npm run lint
```

## 参考にさせていただいたサイト

- https://zenn.dev/lirais/articles/6b28a6b1c3e918
- https://zenn.dev/junyaokabe/articles/latex-environment
