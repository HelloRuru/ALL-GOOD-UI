<h1 align="center">All-Good-UI</h1>

<p align="center">
  <strong>Miranda — 辛口な UI エキスパートスキル、Claude Code 専用。</strong><br>
  あらゆる欠陥を見抜き、自ら修正し、あなたの UI を本番レベルに仕上げます。<br>
  読めば分かる <code>.md</code> ファイルだけで構成。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-D4A5A5?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/claude_code-skill-B8A9C9?style=flat-square" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/dependencies-zero-A8B5A0?style=flat-square" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/files-13%20docs-E8B4B8?style=flat-square" alt="13 Documents">
</p>

<p align="center">
  <a href="README.md">English</a> &nbsp;|&nbsp; <a href="README.zh-TW.md">繁體中文</a> &nbsp;|&nbsp; <b>日本語</b>
</p>

---

## 課題

- AI が作った UI は AI っぽく見える —— 完璧な対称性、汎用カード、無難な配色、個性ゼロ
- デザインルールはあなたの頭の中にあり、システム化されていない —— ページごとに品質がバラバラ
- アクセシビリティ、SEO、レスポンシブ、アニメーション性能 —— 毎回手動で確認するには多すぎる
- リリースしてから、モバイルでコントラストが壊れていた、ボタンにフォーカスリングがなかった、と気づく

---

## 解決策

All-Good-UI は **Miranda** をインストールします。完璧な審美眼を持ち、凡庸さを一切許さないシニア UI エキスパートです。5人の専門サブエージェントを率い、並列で作業します。

### :busts_in_silhouette: チーム

| 名前 | 役割 | 担当 |
| :--- | :--- | :--- |
| **Miranda** | Creative Director | チームの指揮、ユーザーインタビュー、デザイン判断、成果の統合 |
| **Emily**（エミリー） | Visual Lead | タイポグラフィ、カラーシステム、スペーシング、視覚的階層、ダークモード |
| **Serena**（セレーナ） | Art Director | アイコン、アニメーション、トランジション、マイクロインタラクション、装飾要素 |
| **Victor**（ヴィクター） | Senior Auditor | 品質監査、AI っぽさの検出、アンチパターンスキャン、最終仕上げ |
| **Jocelyn**（ジョスリン） | Layout Engineer | レスポンシブデザイン、グリッドシステム、アクセシビリティ、キーボードナビゲーション |
| **Andy**（アンディ） | SEO & Deploy | SEO / AIO / GEO / SGE メタデータ、構造化データ、Core Web Vitals、デプロイ前チェック |

### :sparkles: Miranda にできること

| 機能 | 説明 |
| :--- | :--- |
| ゼロから構築 | インタビュー、デザインシステム生成、フルページ構築 |
| 既存ページの再設計 | 問題の診断、修正、監査 |
| 複数バリアント比較 | 3〜5 のデザイン方向を生成し、自由に組み合わせ |
| 自動品質チェック | アクセシビリティ、AI っぽさ、パフォーマンス、レスポンシブ、SEO —— ビルド後に自動実行 |
| 重大度に基づく対応 | 致命的な問題は自動修正、好みの問題はあなたの判断に委ねる |
| 本番レベルの納品 | そのままデプロイできるコード。SEO、a11y、パフォーマンス対応済み |

---

## :package: インストール

**ステップ 1** —— Clone またはコピーして Claude Code のスキルディレクトリへ：

```bash
git clone https://github.com/HelloRuru/ALL-GOOD-UI.git ~/.claude/skills/all-good-ui
```

**ステップ 2** —— 以上です。会話を開始すると Miranda が自動的に起動します。

**ステップ 3（任意）** —— Better Icons MCP をインストールして 200,000 以上のアイコン検索を有効化：

<details>
<summary><strong>クリックして展開</strong></summary>

`~/.claude/settings.json` に追加：

```json
{
  "mcpServers": {
    "better-icons": {
      "command": "npx",
      "args": ["-y", "better-icons"]
    }
  }
}
```

</details>

---

## :brain: Miranda の仕組み

Miranda は自動的に起動し、構造化されたワークフローに従います：

**フェーズ 0：検出** —— プロジェクトをスキャンし、フレームワーク、パッケージマネージャー、スタイリングシステム、既存のデザイントークンを特定します。

**フェーズ 1：インタビュー** —— まず使用言語（英語または中国語）を確認し、インタビューの詳細度を選択してもらいます。クイックモード（3〜5 問）またはフルモード（8〜12 問）。

**フェーズ 2：ビルド** —— チームを並列で派遣します。Emily は視覚面、Serena はモーション、Jocelyn はレイアウト、Andy は SEO を担当。同時進行で、順番待ちではありません。

**フェーズ 3：自動監査** —— Victor がアクセシビリティ、AI っぽさの検出、アニメーション性能、レスポンシブ対応、SEO 完全性を網羅する品質チェックを自動実行します。

**フェーズ 4：修正** —— 致命的な問題は即座に修正。フォントサイズの好みなど主観的な微調整は、あなたの判断に委ねます。

**フェーズ 5：納品** —— そのままデプロイできる本番レベルのコード。

---

## :shield: 2つのモード

| モード | 使用場面 | 動作 |
| :--- | :------- | :--- |
| **ボスモード（Boss Mode）** | 既存のデザインシステムがない、または Miranda に主導を任せたい場合 | Miranda が全てのデザイン判断を行います。意見が対立した場合は Miranda の基準が優先されます。 |
| **コンサルタントモード（Consultant Mode）** | 独自のブランド / デザインシステムがある場合 | Miranda はあなたの制約を尊重しますが、客観的に壊れているもの（コントラスト、a11y、パフォーマンス）は指摘します。 |

---

## :open_file_folder: ファイル構成

```
all-good-ui/
  SKILL.md                        # メインエントリ —— ペルソナ、ワークフロー、チーム、コマンド
  reference/
    typography.md                  # フォントスタック、サイズ、行間、読み込み
    color.md                       # カラーシステム、コントラスト、ダークモード、色彩理論
    spacing.md                     # 4pt グリッド、スペーシングスケール、視覚リズム
    motion.md                      # アニメーションタイミング、イージング、パフォーマンス、スプリング
    interaction.md                 # 8つの状態、フォーム、フォーカス、ローディング、エラー
    responsive.md                  # モバイルファースト、ブレークポイント、コンテナクエリ
    accessibility.md               # WCAG AA、ARIA、キーボード、フォーカス管理
    metadata-seo.md                # SEO / AIO / GEO / SGE、構造化データ、OG
    anti-patterns.md               # AI っぽさチェックリスト、デザインアンチパターン
  workflow/
    audit.md                       # 品質監査手順（18 カテゴリ）
    design-lab.md                  # マルチバリアント生成と比較
    icons.md                       # アイコン選定 + Better Icons MCP 連携
```

---

## :speech_balloon: コマンド

| English | 日本語 | 機能 |
| :------ | :----- | :--- |
| "Check this" | 「チェックして」 | Victor がフル監査を実行 |
| "Build a page" | 「ページを作って」 | フェーズ 1 からのフルビルドワークフロー |
| "Fix this" | 「直して」 | Miranda が診断して修正 |
| "Show me options" | 「選択肢を見せて」 | 3〜5 のバリアントを生成して比較 |
| "Be the boss" | 「あなたが主導して」 | ボスモードに切り替え |
| "Just advise" | 「アドバイスだけで」 | コンサルタントモードに切り替え |
| "Deploy check" | 「デプロイ前チェック」 | Andy がデプロイ前監査を実行 |
| "Too much AI" | 「AI っぽすぎる」 | Victor が AI っぽさパターンをスキャン |

---

## :wrench: カスタマイズ

| 変更したいもの | 変更先 |
| :------------- | :----- |
| Miranda の性格 | `SKILL.md` > Persona セクション |
| チームメンバー | `SKILL.md` > The Team セクション |
| タイポグラフィルール | `reference/typography.md` |
| カラーシステム | `reference/color.md` |
| 「致命的」の基準 | `SKILL.md` > Phase 4: Severity-Based Action |
| 監査チェックリスト | `workflow/audit.md` |
| アイコンの好み | `workflow/icons.md` |

---

## :bulb: 設計思想

**なぜルールだけでなくペルソナを使うのか？**
ドキュメントに書かれたルールは読み飛ばされます。意見を持ったキャラクターこそ実際に従われます。Miranda は何が問題かを列挙するだけでなく、態度を持って自ら修正します。だからこそアウトプットが印象に残り、一貫性が保たれます。

**なぜサブエージェントを使うのか？**
デザインは多くの領域に同時に関わります —— カラー、レイアウト、アクセシビリティ、SEO。専門エージェントによる並列処理は、単一パスよりも速く、徹底的です。

**なぜ「AI っぽさの検出」が必要なのか？**
AI 生成 UI の最大の特徴は、AI っぽく見えることです。完璧な対称性、汎用的な 3 カラムカード、無難なブルーグレーの配色。Miranda のチームはこれらのパターンを検出し、打ち破ります。

---

## :pray: インスピレーションとクレジット

> **全てのコンテンツはゼロから書き下ろしました。** ソースコードのコピーは一切ありません。Miranda のデザイン知識は、以下のプロジェクトが教える原則から統合したものです。

| プロジェクト | 着想を得た概念 | リンク |
| :----------- | :------------- | :----- |
| Impeccable | デザイン科学、アンチパターン、7 ドメイン参照システム | [Website](https://impeccable.style/) |
| Taste Skill | 審美基準、AI っぽさ検出、スタイルプリセット | [GitHub](https://github.com/Leonxlnx/taste-skill) |
| Superdesign | 自動検出、バリアント生成、デザインシステム雛形 | [Website](https://app.superdesign.dev/) |
| UI Skills | ベースライン UI、アクセシビリティ、メタデータ、モーション性能 | [Website](https://www.ui-skills.com/) |
| Better Icons | 20 万以上のアイコン検索（MCP 経由） | [GitHub](https://github.com/better-auth/better-icons) |
| Design Plugin | マルチバリアント比較、フィードバック収集ワークフロー | [GitHub](https://github.com/0xdesign/design-plugin) |

---

## 必要環境

- [Claude Code](https://claude.ai/claude-code)（CLI または VS Code 拡張機能）
- Node.js 18+（Better Icons MCP を使用する場合のみ）

## ライセンス

MIT —— 詳細は [LICENSE](LICENSE) を参照。

---

<p align="center">
  Made by <a href="https://ohruru.com">HelloRuru</a> -- because good UI shouldn't need an explanation.
</p>
