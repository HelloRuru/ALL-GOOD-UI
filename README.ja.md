<h1 align="center">All-Good-UI</h1>

<p align="center">
  <strong>Miranda（ミランダ）— 毒舌な UI エキスパートスキル、Claude Code 専用。</strong><br>
  あらゆる欠陥を見抜き、自ら修正し、本番対応の UI に仕上げます。
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

- AI が作った UI は AI が作ったように見える——完璧な対称性、汎用カード、無難な配色、個性ゼロ
- デザインルールが頭の中にしかない——ページを作るたびに結果がバラバラ
- アクセシビリティ、SEO、レスポンシブ、アニメーション性能——毎回手動チェックするには多すぎる
- リリースした後で、モバイルでコントラストが崩れていて、ボタンにフォーカスリングがないことに気づく

---

## :mega: ミランダの呼び方

3 つの方法があります。やりやすい方法を選んでください。

### 1. 名前で呼ぶ

```text
Miranda, build me a landing page.
ミランダ、ランディングページを作って。
```

### 2. UI 関連の作業を頼む——自動的に登場します

```text
Help me fix this page layout.
このレイアウトを直して。
Check my site's accessibility.
アクセシビリティをチェックして。
```

UI に関するリクエストであればミランダが自動的に起動します。名前を呼ぶ必要はありません——彼女は常にデザイン作業を待ち構えています。

### 3. スラッシュコマンド

```text
/all-good-ui
```

### トリガー一覧

| English | 日本語 |
| :------ | :----- |
| "Miranda" | 「ミランダ」 |
| "build a page" / "make a page" / "landing page" | 「ページを作って」「LP を作って」 |
| "fix this" / "fix the design" | 「これを直して」「デザインがダサい」 |
| "check this" / "audit" | 「チェックして」「監査して」 |
| "redesign" / "design system" | 「デザインシステムを作って」 |
| "show me options" / "show me versions" | 「いくつかバリエーションを見せて」 |
| "be the boss" / "just advise" | 「ボスモードで」「アドバイザーモードで」 |
| "deploy check" | 「デプロイ前チェック」 |
| "too much AI" / "looks like AI" | 「AI っぽすぎる」 |
| "quick start" / "full interview" | 「クイックスタート」「フルインタビュー」 |

---

## :movie_camera: ミランダの動作例

インストール後、会話を始めるだけです。ミランダがすぐに主導権を握ります：

```text
あなた：  コーヒーショップのランディングページが欲しいんだけど。

ミランダ：  英語と日本語、どっち？早く決めて。

あなた：  日本語で。

ミランダ：  どこまで丁寧にやる？ちゃんとインタビューする——ブランドカラー、
            ターゲット層、全部聞く——か、作りながら決めるか。どっちがいい？

あなた：  作りながら決めよう。

ミランダ：  既存のブランドカラーとフォントはある？それともゼロから？

あなた：  ゼロから。

ミランダ：  了解。私が決める。複数バリエーションを見て比較したい？
            それとも私に任せる？

あなた：  バリエーションを見せて。

ミランダ：  少し待って。

            ┌─ Emily（エミリー／ビジュアルリード）：カラーパレット + タイポグラフィ構築中...
            ├─ Serena（セレーナ／アートディレクター）：アイコン選定 + アニメーション設計中...
            ├─ Jocelyn（ジョスリン／レイアウトエンジニア）：レスポンシブグリッド構築中...
            └─ Andy（アンディ／SEO & デプロイ）：メタデータ + JSON-LD 準備中...

            [4 名がサブエージェントとして並行作業中]

ミランダ：  できた。3 つのバリアントを作ったわ：

            バリアント A — クリーンなエディトリアル。余白たっぷり、セリフ見出し、
            写真重視。高級シングルオリジン専門店向け。

            バリアント B — 温かくて居心地がいい。丸角、アースカラー、手描き
            アイコンのアクセント。近所のカフェ向け。

            バリアント C — 大胆でモダン。ダーク背景、シャープなタイポグラフィ、
            強い CTA。プレミアム感を出したいチェーン店向け。

            どの方向がいい？ミックスもOK：「A のレイアウト + B の配色」。

あなた：  A のレイアウト + B の配色で。

ミランダ：  合成中...

            ┌─ Victor（ヴィクター／シニアオーディター）：品質チェック実行中...
            │   ✓ アクセシビリティ：WCAG AA 合格
            │   ✓ AI っぽさテスト：合格（非対称レイアウト、個性あり）
            │   ✓ レスポンシブ：モバイル検証済み
            │   ✓ SEO：title、OG、JSON-LD 完備
            │   ✗ フッターリンクのコントラスト：3.8:1（4.5:1 必要）— 修正済み
            └─ 完了。

ミランダ：  ランディングページよ。フッターリンクのコントラストが 3.8:1 だった。
            許容できない。直しておいた。感謝は不要。

            デプロイ準備完了。
```

---

## ソリューション

All-Good-UI がインストールするのは **Miranda（ミランダ）**、完璧な審美眼と凡庸さへの容赦ないシニア UI エキスパートです。5 名の専門サブエージェントを率い、並行で作業します。

### :busts_in_silhouette: チーム

| 名前 | 役割 | 担当 |
| :--- | :--- | :--- |
| **Miranda（ミランダ）** | クリエイティブディレクター | チーム統括、ユーザーインタビュー、デザイン判断、成果統合 |
| **Emily（エミリー）** | ビジュアルリード | タイポグラフィ、カラーシステム、スペーシング、視覚的階層、ダークモード |
| **Serena（セレーナ）** | アートディレクター | アイコン、アニメーション、トランジション、マイクロインタラクション、装飾要素 |
| **Victor（ヴィクター）** | シニアオーディター | 品質監査、AI っぽさ検出、アンチパターンスキャン、最終調整 |
| **Jocelyn（ジョスリン）** | レイアウトエンジニア | レスポンシブデザイン、グリッドシステム、アクセシビリティ、キーボードナビゲーション |
| **Andy（アンディ）** | SEO & デプロイ | SEO / AIO / GEO / SGE メタデータ、構造化データ、Core Web Vitals、デプロイ前チェック |

### :sparkles: ミランダにできること

| 機能 | 説明 |
| :--- | :--- |
| ゼロから構築 | インタビュー、デザインシステム生成、フルページ構築 |
| 既存ページの再設計 | 問題診断、修正、監査 |
| 複数バリアント比較 | 3〜5 つのデザイン方向を生成、ミックス＆マッチ可能 |
| 自動品質チェック | アクセシビリティ、AI っぽさ、パフォーマンス、レスポンシブ、SEO——ビルドごとに自動実行 |
| 重大度に応じた対応 | 致命的な問題は自動修正、好みの問題はあなたの判断を仰ぐ |
| 本番対応の成果物 | そのままデプロイ可能。SEO、a11y、パフォーマンス対応済み |

---

## :package: インストール

**ステップ 1** -- Claude Code のスキルディレクトリにクローン：

```bash
git clone https://github.com/HelloRuru/ALL-GOOD-UI.git ~/.claude/skills/all-good-ui
```

**ステップ 2** -- 自動トリガーフックを登録。ミランダの名前や UI 関連キーワードで自動起動するようにします：

<details>
<summary><strong>クリックしてフック設定を表示</strong></summary>

`~/.claude/settings.json` の `"hooks"` セクションに追加：

```json
{
  "hooks": {
    "UserPromptSubmit": [
      {
        "matcher": "*",
        "hooks": [
          {
            "type": "command",
            "command": "node \"~/.claude/skills/all-good-ui/hooks/miranda-trigger.js\""
          }
        ]
      }
    ]
  }
}
```

必要に応じて `~` を実際のホームディレクトリパスに置き換えてください。

</details>

**ステップ 3** -- 完了。「ミランダ」と言うか、UI に関する質問をすれば、彼女が対応します。

**ステップ 4（任意）** -- [Claude Teams Go](https://github.com/HelloRuru/claude-teams-go) と組み合わせて、構造化されたマルチエージェントオーケストレーションを実現：

<details>
<summary><strong>クリックして展開</strong></summary>

Teams Go は Claude Code 向けのブループリントベースのワークフローエンジンです。ミランダの 5 名のサブエージェントを、品質ゲートとリトライロジックを備えた協調チームとして派遣できます。

```bash
git clone https://github.com/HelloRuru/claude-teams-go.git ~/claude-teams-go
```

付属のブループリントをコピー：

```bash
cp ~/.claude/skills/all-good-ui/hooks/miranda-blueprint.md ~/claude-teams-go/blueprints/
```

セットアップの詳細は [Claude Teams Go README](https://github.com/HelloRuru/claude-teams-go) を参照してください。

</details>

**ステップ 5（任意）** -- Better Icons MCP をインストールして 200,000 以上のアイコン検索を利用：

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

## :brain: ミランダの仕組み

ミランダは自動的に起動し、構造化されたワークフローに従います：

**フェーズ 0：検出** -- プロジェクトをスキャンし、フレームワーク、パッケージマネージャー、スタイリングシステム、既存のデザイントークンを特定します。

**フェーズ 1：インタビュー** -- 使用言語（英語・中国語・日本語）を確認し、インタビューの深さを選択。クイックモード（3〜5 問）またはフルモード（8〜12 問）。

**フェーズ 2：ビルド** -- チームを並行で派遣。Emily がビジュアル、Serena がモーション、Jocelyn がレイアウト、Andy が SEO を担当。順番ではなく、同時に作業します。

**フェーズ 3：自動監査** -- Victor がアクセシビリティ、AI っぽさ検出、アニメーションパフォーマンス、レスポンシブ動作、SEO 完全性をカバーする品質チェックを自動実行。

**フェーズ 4：修正** -- 致命的な問題は即座に修正。フォントサイズの好みや主観的な調整はあなたの判断を仰ぎます。

**フェーズ 5：納品** -- そのままデプロイ可能な本番対応コード。

---

## :shield: 2 つのモード

| モード | 使い分け | 動作 |
| :----- | :------- | :--- |
| **ボスモード** | 既存のデザインシステムがない、またはミランダに主導させたい場合 | ミランダが全デザイン判断を行う。意見が食い違えば、彼女の基準が優先される。 |
| **アドバイザーモード** | 自分のブランド／デザインシステムがある場合 | ミランダはあなたの制約を尊重しつつ、客観的に問題のある箇所（コントラスト、a11y、パフォーマンス）は指摘する。 |

---

## :open_file_folder: ファイル構成

```text
all-good-ui/
  SKILL.md                        # メインエントリ——ペルソナ、ワークフロー、チーム、コマンド
  reference/
    typography.md                  # フォントスタック、サイズ、行間、読み込み
    color.md                       # カラーシステム、コントラスト、ダークモード、配色理論
    spacing.md                     # 4pt グリッド、スペーシングスケール、視覚的リズム
    motion.md                      # アニメーションタイミング、イージング、パフォーマンス、スプリング
    interaction.md                 # 8 つの状態、フォーム、フォーカス、ローディング、エラー
    responsive.md                  # モバイルファースト、ブレークポイント、コンテナクエリ
    accessibility.md               # WCAG AA、ARIA、キーボード、フォーカス管理
    metadata-seo.md                # SEO / AIO / GEO / SGE、構造化データ、OG
    anti-patterns.md               # AI っぽさチェックリスト、デザインアンチパターン
  workflow/
    audit.md                       # 品質監査手順（18 カテゴリ）
    design-lab.md                  # 複数バリアント生成と比較
    icons.md                       # アイコン選定 + Better Icons MCP 連携
```

---

## :speech_balloon: コマンド

| English | 日本語 | 機能 |
| :------ | :----- | :--- |
| "Check this" | 「チェックして」 | Victor がフル監査を実行 |
| "Build a page" | 「ページを作って」 | フェーズ 1 からフルビルド |
| "Fix this" | 「これを直して」 | ミランダが診断して修正 |
| "Show me options" | 「バリエーションを見せて」 | 3〜5 つのバリアントを生成して比較 |
| "Be the boss" | 「ボスモードで」 | ボスモードに切り替え |
| "Just advise" | 「アドバイザーモードで」 | アドバイザーモードに切り替え |
| "Quick start" | 「クイックスタート」 | 最小限のインタビューで開始 |
| "Full interview" | 「フルインタビュー」 | フルモード、全部聞く |
| "Set up my design system" | 「デザインシステムを作って」 | ブランドをゼロから生成 |
| "Deploy check" | 「デプロイ前チェック」 | Andy がデプロイ前監査を実行 |
| "Too much AI" | 「AI っぽすぎる」 | Victor が AI っぽさパターンをスキャン |

---

## :wrench: カスタマイズ

| 変更したいもの | 場所 |
| :------------- | :--- |
| ミランダの性格 | `SKILL.md` > Persona セクション |
| チームメンバー | `SKILL.md` > The Team セクション |
| タイポグラフィルール | `reference/typography.md` |
| カラーシステム | `reference/color.md` |
| 「致命的」の基準 | `SKILL.md` > Phase 4: Severity-Based Action |
| 監査チェックリスト | `workflow/audit.md` |
| アイコンの好み | `workflow/icons.md` |

---

## :bulb: デザイン哲学

**なぜルールだけでなくペルソナを使うのか？**
ドキュメントに書かれたルールは読み飛ばされる。意見を持ったキャラクターなら実際に守られる。ミランダは問題を列挙するだけでなく、態度を込めて修正する。だからアウトプットに印象が残り、一貫性が保たれる。

**なぜサブエージェントを使うのか？**
デザインは多くの領域に同時に関わる——色、レイアウト、アクセシビリティ、SEO。専門のエージェントを並行で走らせる方が、1 回のパスですべてをこなすより速く、徹底的になる。

**なぜ「AI っぽさ検出」が必要なのか？**
AI が作った UI の最大の特徴は、AI が作ったように見えること。完璧な対称性、汎用的な 3 カラムカード、無難なブルーグレーのパレット。ミランダのチームはこれらのパターンを特定し、意図的に壊す。

---

## :pray: インスピレーション & クレジット

> **すべてのコンテンツはゼロから書き下ろしました。** ソースコードのコピーはありません。ミランダのデザイン知識は、以下のプロジェクトが教える原則から合成されたものです。

| プロジェクト | 着想を得たコンセプト | リンク |
| :----------- | :------------------- | :----- |
| Impeccable | デザインサイエンス、アンチパターン、7 ドメイン参照システム | [Website](https://impeccable.style/) |
| Taste Skill | 審美基準、AI っぽさ検出、スタイルプリセット | [GitHub](https://github.com/Leonxlnx/taste-skill) |
| Superdesign | 自動検出、バリアント生成、デザインシステムスキャフォールディング | [Website](https://app.superdesign.dev/) |
| UI Skills | ベースライン UI、アクセシビリティ、メタデータ、モーションパフォーマンス | [Website](https://www.ui-skills.com/) |
| Better Icons | MCP 経由で 200k 以上のアイコン検索 | [GitHub](https://github.com/better-auth/better-icons) |
| Design Plugin | 複数バリアント比較、フィードバック収集ワークフロー | [GitHub](https://github.com/0xdesign/design-plugin) |

---

## 要件

- [Claude Code](https://claude.ai/claude-code)（CLI または VS Code 拡張機能）
- Node.js 18+（Better Icons MCP を使用する場合のみ）

## ライセンス

MIT -- 詳細は [LICENSE](LICENSE) を参照。

---

<p align="center">
  Made by <a href="https://ohruru.com">HelloRuru</a> -- 良い UI に説明は要らない。
</p>
