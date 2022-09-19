# Jekyll PaperCSS Theme

## Favicons

Generate your favicons using [a favicon generator](https://favicon.io) and add them to your `source/images/favicons` folder.

This theme has support for:

* apple-touch-icon.png
* favicon-32x32.png
* favicon-16x16.png
* favicon.png
* favicon.ico
* logo.svg

## diff.blog

[diff.[blog](https://diff.blog/) is similar to Medium, but it's only for showing blog feeds, not hosting them. On their website, they advertise themselves as "a platform that helps you discover and follow amazing developer blogs. Whether your interests are in Python, Rust, AI, Distributed Systems or XYZ diff.blog has got amazing blogs for you to follow!"

You can check out more on their [about page](https://diff.blog/FAQ/).

You can use diff.blog with this theme by adding `diff_blog: CODE` to your theme config file. You can find your plugin code by going [here](https://dif.blog/plugin/) and copying the 50-character code.

```javascript
<script id="diffblog-plugin-script" async="false" src="https://diff.blog/static/js/diffblog_plugin_v1.js"></script> 
<script>
  document.getElementById("diffblog-plugin-script").addEventListener("load", function () {
    DiffBlog(
      "q7f864hffi8m218eaq6d623sezfgkz1vzfva4oxjeyxq9l2dwp" // Copy this
    );
  });
</script>
```

## Comments

At the current moment, this theme only supports [utterances](https://utteranc.es/) (mostly because I haven't used anything else). If you know the scripts for others, go ahead and open up a pull request.

```yml
utterances:
  repo: [ENTER REPO HERE] # Github repository owner and name
  # Available values: pathname | url | title | og:title
  issue_term: pathname
  # Available values: github-light | github-dark | preferred-color-scheme | github-dark-orange | icy-dark | dark-blue | photon-dark | boxy-light
  theme: preferred-color-scheme
```

## TODO

* Word Count
