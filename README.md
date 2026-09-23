# オカリナ譜

12穴アルトC管オカリナ用のTAB譜Webアプリ。指の図と音の長さで楽譜を表示し、マイクで音程を判定しながら練習できる。

## 機能
- スコアの作成・編集（音・休符・区切り、½〜4拍）
- お手本再生 / 合うまで待つ練習 / テンポで採点
- マイクによる音程判定とチューナー表示

## 使い方
`index.html` をブラウザで開くだけ。ビルド不要。
GitHub Pages へは `.github/workflows/pages.yml` で `main` への push 時に自動デプロイされる。
初回のみ Settings → Pages → Build and deployment の Source を「GitHub Actions」に設定する。
公開URL: https://enawork.github.io/ocarina-fu/

## メモ
- スコアはブラウザの localStorage に保存される
- マイクは https か localhost でのみ動作
- 半音（#・♭）は未対応
