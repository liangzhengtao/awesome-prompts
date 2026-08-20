[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md)

# 🚀 Awesome Prompts

**開発者・クリエイター・プロフェッショナル向けの実践済み AI プロンプト 150 以上。コピペするだけで結果が出る。**

---

<p align="center">
  <img src="https://img.shields.io/badge/prompts-150+-blue" alt="150+ Prompts">
  <img src="https://img.shields.io/badge/categories-5-green" alt="5 Categories">
  <img src="https://img.shields.io/badge/license-MIT-red" alt="MIT License">
</p>

## 🤔 なぜ Awesome Prompts なのか？

### Before（曖昧なプロンプト）❌

```
帮我写个代码审查
```

### After（正確なプロンプト）✅

```
あなたは経験豊富なセキュリティエンジニアです。以下のコードに対して OWASP Top 10 のセキュリティレビューを実施してください。

言語：Python
フレームワーク：Django
コード：
[paste your code]

以下のフォーマットで出力してください：
1. 🔴 クリティカル（Critical）
2. 🟠 ハイ（High）
3. 🟡 ミディアム（Medium）
4. 🔵 ロウ（Low）

各問題について以下を含めてください：問題の説明、リスクレベル、攻撃シナリオ、修正提案（コード例付き）
```

**結果：毎回 10 倍良い出力が得られる。**

---

## 📂 カテゴリ

<table>
<tr>
<td width="50%">

### 💻 プログラミング
| プロンプトファイル | 内容 |
|-------------------|------|
| [コードレビュー](prompts/编程开发/code-review.md) | セキュリティ監査、パフォーマンス、可読性、アーキテクチャ |
| [デバッグ](prompts/编程开发/debugging.md) | エラー分析、スタックトレース、根本原因分析 |
| [リファクタリング](prompts/编程开发/refactoring.md) | メソッド抽出、条件簡素化、命名最適化 |
| [ドキュメント](prompts/编程开发/documentation.md) | README、API ドキュメント、コードコメント |

</td>
<td width="50%">

### ✍️ コンテンツ制作
| プロンプトファイル | 内容 |
|-------------------|------|
| [ブログ執筆](prompts/内容创作/blog-writing.md) | アウトライン、フック、SEO、結論 |
| [ソーシャルメディア](prompts/内容创作/social-media.md) | Twitter、LinkedIn、Instagram、TikTok |
| [メールシーケンス](prompts/内容创作/email-sequences.md) | ウェルカムシーケンス、ナーチャリング、セールス、再活性化 |

</td>
</tr>
<tr>
<td width="50%">

### 💼 ビジネス
| プロンプトファイル | 内容 |
|-------------------|------|
| [ビジネス戦略](prompts/商业办公/business-strategy.md) | SWOT、競合分析、市場調査 |
| [プレゼンテーション](prompts/商业办公/presentation.md) | スライド、スピーチノート、Q&A |
| [プロジェクト管理](prompts/商业办公/project-management.md) | 要件、リスク、レポート、振り返り |

</td>
<td width="50%">

### 📚 教育・学習
| プロンプトファイル | 内容 |
|-------------------|------|
| [学習アシスタント](prompts/学习教育/study-assistant.md) | 概念説明、フラッシュカード、テスト、学習計画 |
| [教育支援](prompts/学习教育/teaching.md) | 授業計画、評価基準、学生へのフィードバック |
| [リサーチ](prompts/学习教育/research.md) | 文献レビュー、仮説、研究デザイン |

</td>
</tr>
<tr>
<td colspan="2">

### 🎨 クリエイティブデザイン
| プロンプトファイル | 内容 |
|-------------------|------|
| [画像生成](prompts/创意设计/image-generation.md) | スタイル修飾、構図、品質向上、ネガティブプロンプト（20+ テンプレート） |
| [クリエイティブ執筆](prompts/创意设计/creative-writing.md) | ストーリー冒頭、キャラクター作成、世界観構築、会話（15+ テンプレート） |

</td>
</tr>
</table>

---

## 🚀 クイックスタート

### 1. 閲覧

上記のカテゴリから、ニーズに合ったプロンプトを見つけましょう。

### 2. コピー

プロンプトテンプレートをコピーし、`[VARIABLES]` を具体的な情報に置き換えましょう。

### 3. ペーストして結果を取得

お気に入りの AI ツール（ChatGPT、Claude、Gemini など）に貼り付けて、高品質な結果を取得しましょう。

---

## 📖 使い方ガイド

### 変数

すべてのプロンプトは `[VARIABLES]` を使用しています。置き換えてください：

```
[TOPIC]       → 具体的なトピック
[LANGUAGE]    → プログラミング言語
[AUDIENCE]    → ターゲットオーディエンス
[CODE]        → 実際のコード
```

### ヒント

1. **具体的に**: コンテキストを多く提供するほど、出力の品質が向上します。

2. **反復する**: 最初の出力を起点にして、改善を重ねましょう。

3. **組み合わせる**: 複数のカテゴリのプロンプトを組み合わせて複雑なタスクに対応しましょう。

4. **カスタマイズ**: プロンプトを自分のワークフローとスタイルに合わせて修正しましょう。

---

## 🤝 コントリビュート

コントリビューションを歓迎します！まず[コントリビューションガイド](CONTRIBUTING.md)をご覧ください。

### コントリビュートの方法

- 🆕 新しいプロンプトを追加
- ✏️ 既存のプロンプトを改善
- 🐛 エラーや誤字を修正
- 🌍 翻訳を追加
- ⭐ 他の人と共有

---

## 📊 統計

| カテゴリ | ファイル数 | プロンプト数 |
|----------|-----------|-------------|
| 💻 プログラミング | 4 | 64 |
| ✍️ コンテンツ制作 | 3 | 50+ |
| 💼 ビジネス | 3 | 48+ |
| 📚 教育・学習 | 3 | 50+ |
| 🎨 クリエイティブデザイン | 2 | 35+ |
| **合計** | **15** | **247+** |

---

## 📜 ライセンス

本プロジェクトは MIT ライセンスの下で提供されています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。

---

## ⭐ Star History

このプロジェクトが役に立ったら、Star をお願いします！⭐

---

## 📬 お問い合わせ

- **Issues**: [GitHub Issues](https://github.com/liangzhengtao/awesome-prompts/issues)
- **Discussions**: [GitHub Discussions](https://github.com/liangzhengtao/awesome-prompts/discussions)

---

<p align="center">
  コミュニティが ❤️ を込めて制作<br>
  <a href="#top">トップに戻る ↑</a>
</p>

---
