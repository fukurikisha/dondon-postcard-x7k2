【DonDon.絵葉書メーカー PWA v60 公開手順(GitHub Pages)】
1. GitHubで新しいリポジトリを作る(例: dondon-postcard-x7k2。推測されにくい名前にする)。Public。
2. このフォルダの中身6ファイル(index.html, manifest.webmanifest, sw.js, icon-180/192/512.png)を
   リポジトリ直下にアップロード(Add file > Upload files > Commit)。
3. Settings > Pages > Source: "Deploy from a branch" / Branch: main / (root) > Save。
4. 数分後、https://<ユーザー名>.github.io/<リポジトリ名>/ で開ける。
5. iPhoneのSafariでそのURLを開く > 共有ボタン > 「ホーム画面に追加」。以後はアイコンから起動。
【更新するとき】
- index.html を差し替え、sw.js の VERSION の数字も変えてCommit。スマホは次回起動時に自動で更新される。
【注意】
- ChromeではなくSafariで「ホーム画面に追加」すること。
- 写真は端末内のみで処理され、サーバーへ送信されない。
