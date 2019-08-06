## シンボリックリンクの作成
```bash
# win
cmd
mklink /d "C:\Users\ユーザ名\AppData\Roaming\Code\User\snippets"  "D:\プロジェクトフォルダのパス\visual-studio-code-config\snippets"
```

```bash
# mac
 ln -s /プロジェクトフォルダのパス/visual-studio-code-config/snippets /Users/ユーザ名/Library/Application\ Support/Code/User
```

## 拡張機能
### 汎用
- Bracket Pair Colorizer 2
    - コードブロックをわかりやすくする
- GitLens — Git supercharged
    - 高性能なGUI。行ごとに最終更新者が見れる。コミット間の差分が見やすい。
- Insert Numbers
    - マルチカーソルに連番挿入
- Japanese Language Pack for Visual Studio Code
    - 日本語化
- PlantUML
- PrintCode
- TODO Highlight
### CSV
- Rainbow CSV
### HTML
- Auto Rename Tag
    - 開始タグを変更すると同時に終了タグも変更される
### PDF
- [Markdown PDF - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
    - markdownをPDFに変換できる
- [vscode-pdf - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf)


### 未使用だが使い勝手の良さそうなもの
- Prettier - Code formatter
    - コードフォーマッター
- Quokka.js
    - Lightningコンポーネントには使えず
- Settings Sync
    - 複数のPCで設定を共有
    - 一部PCごとに設定を変えているので使用していない
- https://visualstudio.microsoft.com/ja/services/live-share/?rr=https%3A%2F%2Fdev.to%2Fteamxenox%2Fpro-tips-for-visual-studio-code-to-be-productive-in-2018--1jek%3Futm_source%3Ddigest_mailer%26utm_medium%3Demail%26utm_campaign%3Ddigest_email
    - ソースコードレビュー、ペアプロに
