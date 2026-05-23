# Ayu_p Link Page

Ayu_p 用のシンプルなリンクページです。

AIカバー・オリジナル曲の投稿先や、音楽配信サービスへのリンクをまとめるためのページです。

## ファイル構成

- `index.html`  
  GitHub Pages で公開されるメインページです。

- `style.css`  
  ページのデザインを管理するCSSファイルです。

- `wordpress-body.html`  
  WordPressのカスタムHTMLブロック用に作成した貼り付け版です。
  GitHub Pages公開では基本的に使いません。

- `publish-guide.txt`  
  GitHub Pagesで公開するための初心者向け手順書です。

## URLの変更方法

`index.html` を開き、各リンクの `href="#"` の `#` を公開したいURLに置き換えてください。

例:

```html
<a class="link-button primary" href="https://www.youtube.com/@your-channel" target="_blank" rel="noopener noreferrer">
```

URLがまだ決まっていない場合は、`href="#"` のままで大丈夫です。
