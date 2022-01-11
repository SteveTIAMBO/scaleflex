<!DOCTYPE html>
<html>
  <head>
    <title>JS Cloudimage Responsive Example with lazy load</title>
    <meta charset="UTF-8" />
  </head>

  <body>
    <h2>JS Cloudimage Responsive Example with lazy load</h2>

    <!-- Change src to ci-src for your image -->
    <img ci-src="alain.jpg" ci-ratio="1.5" /></br>
    <img ci-src="ameen-fahmy.jpg" ci-ratio="1.5" /></br>
    <img ci-src="tim-patch.jpg" ci-ratio="1.5" /></br>
    <img ci-src="veeterzy.jpg" ci-ratio="1.5" /></br>
    <img ci-src="dino-reichmuth.jpg" ci-ratio="1.5" /></br>
    <img ci-src="inma-lesielle.jpg" ci-ratio="1.5" />

    <!-- Add lazyload library -->
    <script>
      window.lazySizesConfig = window.lazySizesConfig || {};
      window.lazySizesConfig.init = false;
    </script>
    <script src="https://cdn.scaleflex.it/filerobot/js-cloudimage-responsive/lazysizes.min.js"></script>

    <!-- Add js-cloudimage-responsiv library -->
    <script src="https://cdn.scaleflex.it/plugins/js-cloudimage-responsive/4.5.0/js-cloudimage-responsive.min.js"></script>

    <!-- Initialize cloudimage responsive -->
    <script>
      var cloudimgResponsive = new window.CIResponsive({
        token: "demo",
        baseUrl: "https://cloudimage.public.airstore.io/demo/",
        lazyLoading: true
      });
      window.lazySizes.init();
    </script>
  </body>
</html>




















## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/SteveTIAMBO/scaleflex/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SteveTIAMBO/scaleflex/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.





test
