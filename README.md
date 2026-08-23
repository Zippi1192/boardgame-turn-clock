# ボドゲタイマー v0.7.8

2〜6人対応のボードゲーム用持ち時間タイマーです。SOLO / ONLINE ROOMに対応しています。

## v0.7.8

- 「↩ UNDO」を追加
- 直前の1操作を1回だけ戻せます
- 対象: 手番移動、全体PAUSE/再開、±規定時間、時間リセット、人数、規定時間、名前、カラー
- ONLINE ROOMではUNDO結果も全端末へ同期
- 設定ロック中に設定変更をUNDOする場合はHOSTのみ実行可能

## GitHub Pages更新

既存リポジトリの `index.html` をこのフォルダの `index.html` に差し替えてください。
`firebase-config.js` は現在使っているものをそのまま残してください。
Realtime Databaseルールはv0.7.7から変更ありません。
