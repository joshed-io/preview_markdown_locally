preview_markdown_locally
===============

what is it
----------
preview_markdown_locally illustrates how to give your repository a README.html file that renders your README.md locally so can iterate and preview before you push up to Github.

To see it in action, clone this repository and drop it under any static-file-serving web server. Then navigate to README.html.

If you're seeing this and you're not on github.com, you already have. Congrats ):

The README.html contains a link to Github's bundled stylesheet, and the containers are named to pick it up. This helps me get a better picture of what the documentation will look like, but it's totally optional and you may have other HTML & CSS that you prefer.


Caveats
-------
Github uses Github Flavored Markdown (GFM). markdown.js does not contain these extensions. Thus, you might see slight differences when rendered on Github.

require.js and markdown.js are used in this example for ease of illustration. You can use any JS markdown library and XHR to achieve the same effect.
