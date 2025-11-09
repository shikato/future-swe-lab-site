# 未来S/W&E研究所

某スペースオペラとソフトウェアとIBN5100の研究開発に取り組んでおります。

## サイトについて

このリポジトリは、未来S/W&E研究所の公式サイトのソースコードです。

## GitHub Pagesでの公開方法

1. GitHubにリポジトリをプッシュ
2. リポジトリの Settings > Pages に移動
3. Source で `main` ブランチを選択
4. Save をクリック

数分後、`https://[username].github.io/future-swe-lab-site/` でサイトが公開されます。

## ローカルでの確認方法

```bash
# 任意のHTTPサーバーを起動
python3 -m http.server 8000
# または
npx http-server
```

ブラウザで `http://localhost:8000` を開いてサイトを確認できます。

## ライセンス

© 2021-2024 未来S/W&E研究所 All Rights Reserved.
