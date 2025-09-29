# 📝 Zenn 記事執筆用リポジトリ

このリポジトリは[Zenn](https://zenn.dev/)での技術記事執筆用のワークスペースです。

## 📚 概要

- **著者**: [@shirata](https://zenn.dev/shirata)
- **目的**: 技術記事・本・スクラップの執筆・管理

## 📰 記事/本一覧

- **データ構造とアルゴリズム(執筆中)**  
  記事リンク：(公開後貼り付け予定)  
  編集フォルダ：[/books/data_structure_algorithm/](/books/data_structure_algorithm/)

## 🚀 セットアップ

### 1. Zenn CLI のインストール

```bash
npm install -g zenn-cli
```

### 2. 初期化（初回のみ）

```bash
zenn init
```

### 3. プレビューサーバーの起動

```bash
zenn preview
```

ブラウザで `http://localhost:8000` にアクセスして記事をプレビューできます。

## ✍️ 記事の作成

### 新しい記事を作成

```bash
zenn new:article
```

### 新しい本を作成

```bash
zenn new:book
```

### 新しいスクラップを作成

```bash
zenn new:scrap
```

## 📁 ディレクトリ構成

```
.
├── articles/          # 記事ファイル（.md）
├── books/            # 本のファイル
├── scraps/           # スクラップファイル
├── images/           # 画像ファイル
└── package.json      # 依存関係の管理
```

## 📝 執筆ルール

### ファイル命名規則

- 画像: `images/` フォルダ内に記事別でフォルダ分け

### 記事のメタデータ例

```yaml
---
title: "記事のタイトル"
emoji: "📝"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["javascript", "react", "nodejs"]
published: false # 公開設定
---
```

## 🔗 リンク

- [Zenn アカウント](https://zenn.dev/shirata)
- [Zenn CLI 公式ドキュメント](https://zenn.dev/zenn/articles/zenn-cli-guide)
- [Zenn の執筆ガイド](https://zenn.dev/zenn/articles/markdown-guide)

## 📄 ライセンス

このリポジトリの記事は個人の執筆活動用です。
