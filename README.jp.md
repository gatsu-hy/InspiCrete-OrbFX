<div align="center">

# InspiCrete-OrbFX

**モダンなクロスGPU対応リアルタイムグラフィックス強化プラットフォーム**

ゲームやデスクトップアプリケーション向けに、高性能なリアルタイム映像処理とビジュアル強化を提供します。

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.jp.md)

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![C++](https://img.shields.io/badge/C%2B%2B-20-00599C.svg?logo=cplusplus)
![Qt](https://img.shields.io/badge/Qt-6-41CD52.svg?logo=qt)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6.svg?logo=windows)
![Status](https://img.shields.io/badge/Status-開発中-orange)

</div>

---

## 📖 概要

InspiCrete-OrbFX は **C++20** と **Qt 6** を使用して開発された、モダンなグラフィックス強化プラットフォームです。

ゲームやデスクトップアプリケーション向けに、高性能なリアルタイム画像処理やポストプロセスエフェクトを提供することを目的としています。

GPU メーカー専用ソフトウェアとは異なり、OrbFX は **NVIDIA・AMD・Intel** を含むさまざまな GPU で統一されたビジュアル強化体験を実現することを目指しています。

---

## ✨ 主な機能

### 現在

- Modern Fluent UI
- C++20 ネイティブアーキテクチャ
- Qt 6 ベースのユーザーインターフェース
- モジュール化されたプロジェクト構成

### 開発予定

- 🎨 リアルタイム画像フィルター
- 🎞 LUT（.cube）対応
- 🌈 Camera Raw スタイルのカラー調整
- 💡 HDR 強化
- ✨ Bloom エフェクト
- 🔍 シャープニング
- 🎭 彩度・自然な色補正
- 🎮 ゲーム自動検出
- 💾 プリセット管理
- 🔌 プラグインシステム
- 🌍 多言語対応
- 🌙 ダーク / ライトテーマ
- 🤖 AI による画像強化

---

## 🛠 技術スタック

| 項目 | 技術 |
|------|------|
| 言語 | C++20 |
| フレームワーク | Qt 6 |
| グラフィックス API | DirectX 11 / DirectX 12 |
| シェーダー | HLSL |
| ビルドシステム | CMake |
| 開発環境 | Visual Studio 2022 |
| ライセンス | Apache License 2.0 |

---

## 📂 プロジェクト構成

```text
OrbFX
│
├── .github/
│   ├── workflows/
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
│
├── docs/
├── src/
├── include/
├── ui/
├── shaders/
├── resources/
├── tests/
├── third_party/
│
├── README.md
├── README.zh-CN.md
├── README.ja.md
├── LICENSE
├── NOTICE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CMakeLists.txt
└── .gitignore
```

---

## 🚀 開発ロードマップ

### Phase 1 — 基盤構築

- [x] リポジトリ作成
- [ ] プロジェクトアーキテクチャ
- [ ] Modern Fluent UI
- [ ] 設定システム
- [ ] プリセット管理

### Phase 2 — レンダリング

- [ ] デスクトップキャプチャ
- [ ] GPU レンダリング
- [ ] シェーダーパイプライン
- [ ] DirectX 11 対応

### Phase 3 — グラフィックス強化

- [ ] HDR 強化
- [ ] LUT 対応
- [ ] Bloom
- [ ] シャープニング
- [ ] カラーグレーディング
- [ ] Camera Raw スタイル調整

### Phase 4 — エコシステム

- [ ] プラグイン SDK
- [ ] コミュニティプリセット
- [ ] AI 画像強化
- [ ] DirectX 12 最適化

---

## 📷 スクリーンショット

現在開発中です。

最初のプレビュー版公開後にスクリーンショットを掲載予定です。

---

## ⚡ ビルド方法

### 必要環境

- Windows 11
- Visual Studio 2022
- Qt 6
- CMake
- Git

### リポジトリを取得

```bash
git clone https://github.com/gatsu-hy/InspiCrete-OrbFX.git
```

### ビルド

```bash
mkdir build
cd build

cmake ..

cmake --build . --config Release
```

---

## 📦 インストール

最新バージョンは **Releases** ページからダウンロードしてください。

展開後、以下を実行してください。

```text
OrbFX.exe
```

---

## 🤝 コントリビューション

InspiCrete-OrbFX への貢献を歓迎します。

Pull Request を送信する前に、以下のドキュメントをご確認ください。

- CONTRIBUTING.md
- CODE_OF_CONDUCT.md

バグ報告、機能提案、ドキュメント改善など、あらゆる貢献を歓迎します。

---

## 📜 ライセンス

このプロジェクトは **Apache License 2.0** のもとで公開されています。

詳細は **LICENSE** ファイルをご覧ください。

---

## 🎯 プロジェクトビジョン

InspiCrete-OrbFX は、モダンで拡張性の高いグラフィックス強化プラットフォームを目指しています。

私たちが重視する価値は以下のとおりです。

- 🚀 高性能
- 🎨 モダンな Fluent Design
- 🔧 高い拡張性
- 🖥 GPU ベンダーを問わない互換性
- 🎞 プロフェッショナルな画質

InspiCrete-OrbFX は GPU メーカー製ソフトウェアを置き換えることではなく、すべてのユーザーに統一されたビジュアル強化体験を提供することを目標としています。

---

## ❤️ 謝辞

本プロジェクトは、数多くのオープンソースプロジェクトと開発者コミュニティによって支えられています。

特に以下のプロジェクトに感謝します。

- Qt
- Microsoft
- CMake
- LLVM
- Dear ImGui
- オープンソースコミュニティの皆様

---

<div align="center">

**Made with ❤️ by the InspiCrete Studio**

Copyright © 2026 InspiCrete Studio

Licensed under the Apache License 2.0.

</div>
