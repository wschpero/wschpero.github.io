wschpero.github.io
========

Code for williamschpero.com. This website is:

* Based on the web design of [Jonathan McGlone](https://github.com/jmcglone/jmcglone.github.io).
* Licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/deed.en_US).
* Built with [Bootstrap 3.0](http://getbootstrap.com).
* Powered by [Jekyll](http://jekyllrb.com).

Be sure to change the Google Analytics key and site URL in `_includes/analytics.html` if you fork this code for your website.

```html 
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', '<INSERT GOOGLE KEY HERE>', '<INSERT SITE URL HERE>');
  ga('send', 'pageview');

</script>
```

You will also need to edit `_includes/head.html`, `_includes/header.html`, `about/index.html`, `publications/index.html`, `notes/atom.xml`, `notes/index.html`, `index.html`, `README.md`, and `CNAME` to be specific to you / your site, along with the CV in `cv/` and the image in `img/`.