Hexo-Theme-Wixo
===

Turn your Hexo into a Wiki!

* [Demo](http://hahack.tk/hexo-theme-wixo/)
* [Q&A](http://hahack.tk/hexo-theme-wixo/Docs/qna/)
* [Tag Plugins](http://hahack.tk/hexo-theme-wixo/Docs/tag-plugins/)

## Features ##

* **Simple** - keep it simple and stupid;
* **Bootstrap** - get the power of Twitter Bootstrap with minimal hassle;
* **Notebook** - notebook-aware post arrangement and pagination. A category is a notebook;
* **Scrollspy** - automatically updating ToC targets based on scroll position;
* **Tag plugins** - luxuriant Bootstrap tag plugins, provided by [hexo-tag-bootstrap](https://github.com/wzpan/hexo-tag-bootstrap), including:
  - textcolor - a paragraph of text with specified color;
  - button - a button with target links, text and specified color;
  - label - a label with text and specified color;
  - badge - a badge with text;
  - alert - alert messages with text and specified color;

## Install ##

1) install theme:

``` sh
$ git clone https://github.com/wzpan/hexo-theme-wixo.git themes/wixo
```

2) install [hexo-tag-bootstrap](https://github.com/wzpan/hexo-tag-bootstrap):

``` sh
$ npm install hexo-tag-bootstrap --save
```

## Enable ##

Modify `theme` setting in your `_config.yml` to `wixo`.

## Update ##

``` sh
$ cd themes/wixo
$ git pull
```

## Configuration ##

```
fancybox: true
favicon: favicon.png
google_analytics:
```

* **fancybox** - enable [Fancybox](http://fancyapps.com/fancybox/)
* **google_analytics** - Google Analytics ID

## Front-Matter ##

* **toc** - renders a table of contents

For example:

```
title: Tag Plugins
date: 2014-03-16 10:17:16
categories: Docs
toc: true
---
```

## Todo ##

See [TODO](https://github.com/wzpan/hexo-theme-wixo/wiki/TODO).

## License ##

This theme is provided under [MIT License](http://opensource.org/licenses/MIT).

## Credits ##

* The theme is built based on [Twitter-Bootstrap 3.1.1](getbootstrap.com/3.1.1/);
* The beautiful icons are from [Font Awesome](http://fortawesome.github.io/Font-Awesome/icons/).
