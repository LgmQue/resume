# resume

職務経歴書の公開ページです。

## 仕組み

`LgmQue/resume-app`（Private）の「🌐 公開」ボタンを押すと：

1. DB に保存された職務経歴 JSON を取得
2. GitHub Actions (`publish.yml`) が `index.html` に JSON をインライン埋め込み
3. このリポジトリの `index.html` が更新される
4. GitHub Pages が自動デプロイ

`resume.json` はリポジトリに存在しません。データは `index.html` に直接埋め込まれています。
