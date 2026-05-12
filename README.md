# みちびき（MICHIBIKI）プライバシーポリシー

このリポジトリは、iOSアプリ「みちびき（MICHIBIKI）」のプライバシーポリシーをGitHub Pagesで公開するための最小構成です。

## ファイル構成

- `index.html`：GitHub Pagesで公開するプライバシーポリシーページ
- `privacy-policy.md`：同内容のMarkdown版

## GitHub Pagesでの公開手順

1. GitHubで任意のリポジトリを作成します。
2. このフォルダ内のファイルをリポジトリ直下に配置します。
3. GitHubのリポジトリ画面で `Settings` → `Pages` を開きます。
4. `Build and deployment` で `Deploy from a branch` を選択します。
5. Branchを `main`、folderを `/ (root)` に設定して保存します。
6. 数分後、表示されるGitHub PagesのURLにアクセスし、プライバシーポリシーが表示されることを確認します。
7. App Store Connectの「プライバシーポリシーURL」に、公開されたURLを設定します。

## App Store Connectに設定するURL例

```text
https://<GitHubユーザー名>.github.io/<リポジトリ名>/
```

ユーザー名やリポジトリ名に応じてURLは変わります。

## 更新時の注意

- AdMob、Firebase、独自サーバーなど、利用するSDKやデータ送信先が変わった場合は本文を更新してください。
- App Store Connectの「Appのプライバシー」で申告した内容と、このプライバシーポリシーの内容が矛盾しないようにしてください。
- ATTを将来的に実装する場合は、「トラッキングについて」の記載を見直してください。
