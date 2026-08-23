# TURN CLOCK v0.4

2〜6人対応のボードゲーム用持ち時間タイマーです。

## GitHub Pages で公開する方法

1. GitHub で新しい Public repository を作成します（例: `turn-clock`）。
2. このフォルダ内の `index.html` と `.nojekyll` を repository のルートにアップロードします。
3. repository の `Settings` → `Pages` を開きます。
4. `Build and deployment` の Source を `Deploy from a branch` にします。
5. Branch を `main`、Folder を `/(root)` にして Save します。
6. 反映後、`https://<GitHubユーザー名>.github.io/turn-clock/` で開けます。

## 主な機能

- 2〜6人を切り替え
- 各プレイヤーの残り時間を持ち越し
- 0秒以降はマイナス時間を継続表示
- 全体一時停止 / 再開
- 前の人 / 次の人への手番移動
- 初期時間の変更
- プレイヤー名の変更
- スマホ縦持ち / 横持ちレスポンシブ対応

外部APIやデータベースは使用していません。`index.html` 1枚で動作します。
