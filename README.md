巴哈姆特哈拉開圖器 fixed
=====================

由 [巴哈姆特哈拉開圖器](http://userscripts-mirror.org/scripts/review/142033) by akiratw 修改而來。

> * 在未登入時也可以直接顯示 [巴哈姆特哈啦區](http://forum.gamer.com.tw/) 文章裡的圖片和 YouTube 影片。
> * 跳過巴哈姆特的站外連結警告頁面。

修正
----
* 加入圖片並行載入限制，最多同時載入 3 張圖片，避免一次載入多張圖片時失敗。
* URL matching rule 修正

Install
-------

License
-------
在 userscript 內標示為 MIT，然而原作者的網站已經連不上了，雖然 [wayback machine](https://web.archive.org/web/20150226181127/http://akr.tw/2012/08/bahamut-image-viewer/) 有 blog 文章，但找不到 license file。

Changelog
---------
* 1.2.0
	- Fix include rules.
	- Throttle image loads.
