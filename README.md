# [Center-Loader](http://plugins.rohitkhatri.com/center-loader/)

[Center-Loader](http://plugins.rohitkhatri.com/center-loader/) is an open source, loader plugin to block a box or div to show the process created by [Rohit Khatri](http://rohitkhatri.com/).

## How to Use?

Center-Loader depends on jQuery. Include them both in end of your HTML code:

```html
<script src="js/jquery.js" type="text/javascript"></script>
<script src="js/center-loader.js" type="text/javascript"></script>
```

You can either pass a font awesome icon like

```html
<i class="fa fa-cog fa-spin"></i>
```

Or pass any image or tag and it will be block the container and place the loader in the center.

To show and hide loader:

```js
$('#container').loader('show','<i class="fa fa-cog fa-spin"></i>');
$('#container').loader('hide');

$('#container').loader('show','<img src="img/loader.gif">');
$('#container').loader('hide');
```

## Bugs and Issues

Have a bug or an issue with this plugin? [Open a new issue](https://github.com/rohitkhatri/center-loader/issues) here on GitHub or leave.

## Creator

Center-Loader was created by and is maintained by **Rohit Khatri**, Backend Developer at [Thought Chimp](http://www.thoughtchimp.com/).

* https://twitter.com/devrohitkhatri
* https://github.com/rohitkhatri