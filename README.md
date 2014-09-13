&lt;async-files&gt; element &lt;/async-files&gt;
==========================================

WebComponent that allows to load javascripts and css files asynchronously and store the files in localStorage.


Use guide
--------------
##### Install aync-files component using [bower].
```bash
$ bower install async-files#master

```

#### Use
```html
...
<head>
  <!-- Optional pollyfil-->
  <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.3.4/platform.js"></script>
  <!--Import component-->
  <link rel="import" href="webcomponent/async-files.html">
</head>
<body>
    <async-files
      js='["one.js", "./two.js"]'
      css='["alternative-fonts.css"]'>
    </async-files>
</body>
...
```
License
-------
MIT
