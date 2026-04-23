# V/AIBOU LP

VAIZO第1の柱「V/AIBOU プラットフォーム」のLP。

---

## ⭐ 最新版

**`index.html`** が常に最新・本番候補。これだけ見れば今のLPが分かる。

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
│   └── v3_20260423_ENTER命名前.html
└── .git/                         ← GitHubリポジトリ連携
```

---

## 現状のバージョン

- **v34**（2026-04-24）
- ドメイン表記：`v-aibou.com` / `vaizo.jp`
- 公開前暫定版（PINゲート `0415` 付き）

---

## 本番公開

- **ドメイン**：v-aibou.com
- **実装**：WordPress（Xserver）
- **公開日**：2026-04-24
- **タスクリスト**：[V_AIBOU_LP公開タスクリスト_20260424](https://docs.google.com/document/d/1efy6CozUlgl4NrfumioeIMICGsBR_u9_sNmHdR8H5oY/edit)

---

## プレビュー

- **プレビューURL**：https://y-hashimoto-vaizo.github.io/vaibou-lp-preview/
- **PIN**：`0415`（限定共有中）
- **GitHubリポジトリ**：https://github.com/y-hashimoto-vaizo/vaibou-lp-preview

---

## 編集ルール

- **編集は `index.html` のみ**
- 大きな変更前にスナップショットを取る → `_archive/vN_YYYYMMDD_説明.html` にコピー保存
- git commit はコミットメッセージに `vN` を付ける（例：`v35: 価格改定`）
- `git push` で GitHub Pages 側も自動反映
- PIN保護はクライアント側簡易ガード。本番では削除
