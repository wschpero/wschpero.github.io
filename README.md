wschpero.github.io
========

Code for [williamschpero.com](http://williamschpero.com). This website is:

* Based on the web design of [Jonathan McGlone](https://github.com/jmcglone/jmcglone.github.io).
* Licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/deed.en_US).
* Built with [Bootstrap 3.0](http://getbootstrap.com).
* Powered by [Jekyll](http://jekyllrb.com).

Be sure to change the Google Analytics `TAG_ID' in `_includes/analytics.html` if you fork or otherwise use this code for your website.

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TAG_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'TAG_ID');
</script>
```

You will also need to edit `_includes/head.html`, `_includes/header.html`, `about/index.html`, `bio/index.html`, `research/index.html`, `notes/atom.xml`, `notes/index.html`, `index.html`, `README.md`, and `CNAME` to be specific to you / your site, along with the publication files included in `collections/`, the CV in `cv/`, and the image in `img/`.