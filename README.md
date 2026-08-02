# 招待状 / しおり

軽井沢での挙式にあたって、家族向けに用意した1ページの案内です。
静的HTML1枚のみ。ビルド不要、依存パッケージなし。

## 構成

```
index.html      本体（CSS / JS も内包）
images/         写真の置き場所（README.md に一覧あり）
robots.txt      検索エンジンからのクロールを拒否
.nojekyll       GitHub Pages の Jekyll 処理を無効化
```

## 公開先

<https://s-punny.github.io/karuizawa-nt9wn2/>

## 公開の手順（GitHub Pages）

1. GitHub で `karuizawa-nt9wn2` を Public で作る（初期ファイルは付けない）
2. このフォルダの中身を push する
3. リポジトリの **Settings → Pages** で
   Source を `Deploy from a branch`、Branch を `main` / `/(root)` に設定
4. 数分で公開される

URLを変える場合は `index.html` 冒頭の3か所
（`canonical` / `og:url` / `og:image`）も合わせて直すこと。
ここが合っていないと、LINEで送ったときのサムネイルが出ない。

## 情報の差し替え

未確定の箇所には金色の下線と小さな「仮」が付いている。
`index.html` を `仮` で検索すると該当箇所が全部拾える。

## 注意

GitHub Pages（無料プラン）で公開したページは**URLを知っている人なら誰でも閲覧できる**。
検索避け（`noindex` と `robots.txt`）は入れてあるが、アクセス制限ではない。
氏名・電話番号・住所・日付を載せる際はその前提で判断すること。
