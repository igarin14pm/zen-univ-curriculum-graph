# zen-univ-curriculum-graph

ZEN大学のシラバスとカリキュラム・マップに記載されている前提科目・後継科目を Markdown ファイルに記載し、Quartz でグラフを描画します。

## コントリビュートしたい方へ

学内 Slack で **@いがりん** (作成者) までご連絡ください。

## 動作環境

- Node.js 22

## セットアップ手順

```bash
# リポジトリのクローン
git clone https://github.com/igarin14pm/zen-univ-curriculum-graph.git
cd zen-univ-curriculum-graph.git

# パッケージのインストール
npm i

# Quartz プラグインをインストール
npx quartz plugin install --from-config
```

## 起動方法

```
npx quartz build --serve
```

起動後、`http://localhost:8080` にアクセス

## ライセンス

本リポジトリは [MIT License](./LICENSE.txt) のもとで公開されています。

本リポジトリは以下のライブラリを使用しています。

- [**Quartz**](https://github.com/jackyzha0/quartz)

各ライブラリの権利はそれぞれの開発者に帰属します。
