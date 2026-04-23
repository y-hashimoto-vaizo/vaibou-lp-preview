# V/AIBOU LP

VAIZO第1の柱「V/AIBOU プラットフォーム」のLP。

---

## ⭐ 最新版

**`index.html`** が常に最新・本番候補。これだけ見れば今のLPが分かる。

## 🚀 現行バージョン：**v44**（2026-04-24 最終版）

- ドメイン表記：`v-aibou.com` / `vaizo.jp`
- 公開前暫定版（PINゲート `0415` 付き）
- カラー：白黒エディトリアル + CTAアクセント **#D7481F（バーントシエナ）**
- Heroアニメ：ロゴ1文字落下 → タグラインclip-path wipe → 黒マーカー後書き反転 → オレンジバー一閃 → CTAバウンド

## 🔗 共有リンク

| 用途 | URL |
|------|-----|
| **プレビュー（本番候補）** | https://y-hashimoto-vaizo.github.io/vaibou-lp-preview/ |
| **PIN** | `0415` |
| **GitHubリポジトリ** | https://github.com/y-hashimoto-vaizo/vaibou-lp-preview |
| **公開タスクリスト** | [Google Doc](https://docs.google.com/document/d/1efy6CozUlgl4NrfumioeIMICGsBR_u9_sNmHdR8H5oY/edit) |

---

## ディレクトリ構成

```
V AIBOU_LP/
├── index.html                    ← 【最新版・常にここが正】
├── README.md                     ← このファイル
├── assets/                       ← LP内で使う画像
│   ├── demo-ui.png               (1人分のAIスタッフUIスクショ)
│   └── parallel-team.png         (4人同時稼働のUIスクショ)
├── _archive/                     ← 過去スナップショット（参照のみ、編集禁止）
│   ├── v3_20260422_コピー確定.html
│   ├── v3_20260423_ENTER命名前.html
│   └── v44_20260424_最終版.html  ← ★LP公開用最終スナップショット
└── .git/                         ← GitHubリポジトリ連携
```

---

## セクション構成（17セクション）

1. Hero（東大早慶×専門家×24時間×月3万円 / 黒マーカー演出）
2. SERVICE（10人の会社に100人のプロ・3ポイント）
3. DEMO（4ステップ + 1人分UIスクショ）
4. PARALLEL AI TEAM（4人同時稼働スクショ + 3カード）
5. AI社員カタログ（V/SANBO/V/ENTER WEB/V/SEARCH/V/HOJOKIN + KOHO/KEIRI coming）
6. Price Shock（月150万以上 vs 月3万円〜）
7. Pricing Plans（Start/Unlimited/Enterprise）
8. Add-ons（スポット開発/利用枠追加/カスタム開発）
9. Volume（月5万円で69,000本等）
10. BEFORE/AFTER（6事例カード）
11. WHY VAIZO（3本柱）
12. CASE（自社事例6件）
13. FAQ（8問アコーディオン）
14. SECURITY（AWS+採用企業6+詳細6項目）
15. SUPPORT（3週間伴走・合計135分・0円）
16. Future（組織のサイズとケーパビリティの解放）
17. COMPANY INFO（運営会社・vaizo.jpリンク）

---

## 本番公開予定

- **ドメイン**：v-aibou.com
- **実装**：WordPress（Xserver）
- **公開日**：2026-04-24以降
- **タスクリスト**：[公開タスクDoc](https://docs.google.com/document/d/1efy6CozUlgl4NrfumioeIMICGsBR_u9_sNmHdR8H5oY/edit)

---

## 編集ルール

- **編集は `index.html` のみ**
- 大きな変更前にスナップショット → `_archive/vN_YYYYMMDD_説明.html`
- git commit はコミットメッセージに `vN` を付ける（例：`v45: 価格改定`）
- `git push` で GitHub Pages 側も自動反映
- PIN保護はクライアント側簡易ガード、本番WP移植時に削除
