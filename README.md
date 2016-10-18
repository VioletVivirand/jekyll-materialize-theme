!!!Still Underconstruction!!! Come back and check later please~

## Features

* [Prism.JS](http://prismjs.com)
* [Materialize Framework](http://prismjs.com)
* Tag Archive function with [jekyll-tagging Plugin](https://github.com/pattex/jekyll-tagging)
* Category Archive with some tweaks and custom layout and template
* Paginator

## Recommended Tweek

* Permalink: /:categories/:title.html，然後把文章的資料夾架構改成像 [Variables](http://jekyllrb.com/docs/variables/) 頁面、`page.categories` 部分建議的資料夾架構，這樣子**或許**就可以在每層的資料夾新增 `index.html`，套用特定 Layout 當作 Archive Page

## TODO

* [ScrollSpy](http://materializecss.com/scrollspy.html)
* Category 顯示（參考 Recommended Tweek 裡面的 Permalink 解決方法）
* Paginator
* Redirect（像是把Post 的網址去掉一部份，應該出現什麼頁面，還有 404 Error）
    * https://github.com/jekyll/jekyll-redirect-from，配合設定 [Permalinks](https://jekyllrb.com/docs/configuration/#default-configuration)
        * blog 的網址現在看起來太複雜了，這樣要 Redirect 的東西太多，應該參考 [Wordpress 建議的 permalink 格式來設定](https://www.elegantthemes.com/blog/tips-tricks/wordpress-permalinks)（`/%category%/%postname%/`）
        * 或是用 Archive Plugin [https://github.com/jekyll/jekyll-archives]()

## Future

Wordpress theme 有什麼我就做什麼 ^.<