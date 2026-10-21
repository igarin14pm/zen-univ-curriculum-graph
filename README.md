# zen-univ-curriculum-graph [ARCHIVED]

ZEN大学のシラバスとカリキュラム・マップに記載されている前提科目・後継科目を Markdown ファイルに記載し、Quartz でグラフを描画します。

## EOL (サポート終了について)

当リポジトリは Quartz のフォークという複雑な構造のため、以前から修正が困難な脆弱性を抱えていました。

修正を行おうと数々の試行を行ったのですが、そもそも修正が不可能か、修正を行うとビルドが不可能となる事態が発生してしまいました。

このため、安全性を考え、予定を前倒しして当 Web サイトの公開を終了し、リポジトリそのものを EOL (End of Life: サポート・修正プログラム提供の終了) といたします。

長らくのご愛顧ありがとうございました。以降は Vite + React で構築した "ZEN大 カリキュラム・グラフ (リニューアル版)" をご利用ください。

**"ZEN大 カリキュラム・グラフ (リニューアル版)"**
- **Webページ:** https://zen-univ-curriculum-graph.igarin14pm.com
- **GitHub:** https://github.com/igarin14pm/zen-univ-curriculum-graph-react

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
