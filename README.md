# Jekyllブランクテーマの日本ローカライズ版

[Blank-Theme-Jekyll](https://github.com/garrettboatman/Blank-Theme-Jekyll)の日本ローカライズ版です。

Jekyllのためのブランクテンプレートです。

- 日本語対応
- HTML圧縮をテンプレート使用方式に変更
- SNSアカウントを持っている場合のみOGタグを出力するように変更
- CSS/JSキャッシュクリア用の記述を追加
- 開発環境用ファイルを追加（開発環境ではCSSをminifyせずネストして表示する、等）
- GoogleAnalyticsコード設置用ファイルを追加
- ブラウザCSSリセットを追加
- mt10など、よく使うCSSを追加

## 開発環境ファイルを参照してのserve
JEKYLL_ENV=development jekyll serve --config "_config.yml,_config_dev.yml" --watch

## 本番環境にアップロードするためのbuild
JEKYLL_ENV=production jekyll build --watch
