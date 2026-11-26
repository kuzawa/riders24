# ライダーズ24 サイト

株式会社九澤商会が運営する月極バイク駐車場「ライダーズ24」の静的サイト。
GitHub Pages で公開する前提の、ビルド不要な HTML/CSS のみで構成。

- 本番URL: https://riders24.kuzawashokai.com/
- 構成:
  - `/` ブランドトップ（拠点一覧）
  - `/hikarigaoka/` 田柄光が丘トップ
  - `/hikarigaoka/price/` 料金とご契約
  - `/hikarigaoka/status/` 空き状況
  - `/hikarigaoka/contact/` お問い合わせ・申し込み
  - `/hikarigaoka/qanda/` よくあるご質問

## 更新のしかた

- 空き状況: `hikarigaoka/status/index.html` の表と「現在、空きは◯台です」の文、
  あわせて拠点トップ（`hikarigaoka/index.html`）とブランドトップ（`index.html`）の空き台数表記を直す。
- 料金: `hikarigaoka/price/index.html` と各ページの料金表記を直す。
- 電話番号: 050-6872-6236（Brastel）。全ページに記載あり。

## 公開メモ

- ドメイン riders24.kuzawashokai.com はムームードメイン管理の kuzawashokai.com のサブドメイン。
  ムームーDNSに riders24 の CNAME（→ kuzawa.github.io）を追加し、このリポジトリの Pages 設定に
  カスタムドメインを設定する（CNAME ファイルを置く）。
- kuzawashokai.com ではムームーメールが稼働中のため、MX 等のメール設定には触らない。
