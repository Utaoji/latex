# draftを使って、図の読み込みを省略
プリアンブル部分を
```
\documentclass[uplatex,dvipdfmx]{jsarticle}
(以下略)
```
のようになっているのを
```
\documentclass[uplatex,dvipdfmx,draft]{jsarticle}
(以下略)
```
とするだけ

最後に完成版のpdfを作りたいときは```draft```を削除するだけ
