# バカゲー製作所 (bakage.com)

バカゲー製作所が毎日ゲームを製造する工場です。30秒で遊べるムダなゲームをお届けします。

- 🏭 サイト: https://bakage.com
- 🐦 X: [@bakage_com](https://x.com/bakage_com)

## 仕組み

- `index.html` — トップページ。`games/index.json` を読んでゲーム一覧を表示
- `games/<slug>/` — 1ゲーム1フォルダ(単一HTML完結)
- `games/index.json` — ゲームカタログ(タイトル・説明・出荷日)

push すると GitHub Pages が自動で bakage.com に反映します。
