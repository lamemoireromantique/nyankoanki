# にゃんこ暗記塾 iPad版

## 公開方法（GitHub Pages）
1. GitHubリポジトリの「Add file」→「Upload files」。
2. このフォルダ内の **index.html / kitten.png / icon.png / manifest.webmanifest / sw.js** をリポジトリ直下へアップロード（フォルダごとではなく中身）。
3. Commit changes。
4. Settings → Pages → Deploy from a branch → Branch: main / Folder: /(root) → Save。
5. 発行URLをiPadのSafariで開き、共有 → ホーム画面に追加。

## データについて
問題・正誤履歴・復習予定・猫のレベルはブラウザのlocalStorageに保存されます。
SafariのWebサイトデータ削除や端末故障に備え、アプリ内の「バックアップ」から定期的にJSONを書き出し、iCloud Drive等へ保管してください。
この版はiPad内保存で、自動同期はありません。別端末への同期には別途クラウドDB等の実装が必要です。

## 注意
これはGitHub Pagesで公開するWebアプリです。リポジトリがPublicの場合、ソースファイルは公開されます。学習データは公開リポジトリへ登録せず、アプリを開いた端末のブラウザ内に保存してください。
