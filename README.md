# ランディングページ

- レスポンシブ対応
- リセットCSS
- 「favicon.ico」「apple-touch-icon.png」を設置
- pictureタグによる画像の切り替え
- @keyframesを利用したCSSアニメーションを利用
- パララックスの実装
- JQueryによる要素の表示非表示の切り替え
- スライダーを導入（JQueryプラグイン「slick」）
- Sass導入
- PostCSSを利用してのベンダープレフィックスの自動付与


# clone後の、Sass、PostCSS対応
プロジェクトのクローン後、`npm install` にて、package.jsonに記述されているパッケージをインストールする。

コマンドプロンプトにて、`npm run watch:sass`を実行。scssファイルに編集を加えるたびに、編集が反映されたcss/.cssファイルが作成。

コマンドプロンプトにて、`npm run postcss`を実行。作成済みのcss/.cssファイルにベンダープレフィックスを自動付与。

# 発展
現状「予約ページ」と「お問い合わせ」が実装されていないので、サーバーサイドでこれらの機能を実装することが考えられる。

# 参考
以下、書籍を参考。

『HTML&CSS Webデザイン 現場レベルのコーディング・スキルが身につく実践入門』

『Web制作者のためのSassの教科書』
