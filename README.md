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
  <script src="../platform/platform.js"></script>
  <!--Import component-->
  <link rel="import" href="webcomponent/async-files.html">
</head>
<body>
    <async-files
      js='["//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js", "./1.js"]'
      css='["alternative-fonts.css"]'>
    </async-files>
</body>
...
```
License
-------
MIT
