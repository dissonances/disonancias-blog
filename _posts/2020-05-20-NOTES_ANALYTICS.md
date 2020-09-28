---
title: Implementación de Google Analytics en Jekyll
---

This suppose to be the code for #Jekyll.

```{javascript}
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-152619439-1', 'auto');
  ga('send', 'pageview');
</script>
```

Info from #Google #Analytics website provides the following code:

```{javascript}
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-152619439-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-152619439-1');
</script>
```

Nevertheless, my question was about how to implement the #Jekyll website from GitHub Pages so I wouldn't have to install it in my computer.
I tried to add the files directly to the GitHub repository through GitHub Desktop.
