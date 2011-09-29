preview_markdown_locally
===============

What is it?
----------
preview\_markdown\_locally illustrates how to give your repository a README.html file that renders your README.md locally so can iterate and preview before you push up to Github.

To see it in action, clone this repository and drop it under any static-file-serving web server. Then navigate to README.html.

If you're seeing this and you're not on github.com, you already have. Congrats ):

The README.html contains a hotlink to Github's bundled stylesheet, and the containers are named such that it'll apply properly. This helps me get a better picture of what the documentation will look like on github.com. That said, it's totally optional and you may have other HTML & CSS that you prefer.

Caveats
-------
Github uses Github Flavored Markdown (GFM). The included markdown.js does not contain the GFM extensions. Thus, you might see slight differences when rendered on Github.


