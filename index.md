<!DOCTYPE html>
<html>
  <head>
    <title>JS Cloudimage Responsive Example with lazy load</title>
    <meta charset="UTF-8" />
  </head>

  <body>
    <h2>Steve's JS Cloudimage Responsive Demonstration</h2>

    <!-- To add my standard images -->
    <img src="https://cloudimage.public.airstore.io/demo/ricky-kharawala.jpg" /></br>
    <img src="https://cloudimage.public.airstore.io/demo/jp-valery.jpg"  /></br>
    <img src="https://cloudimage.public.airstore.io/demo/kira-laktionov.jpg" />
    

    <!-- Change src to ci-src for the responsiveness 
    <img ci-src="ricky-kharawala.jpg" ci-ratio="1.5" />
    <img ci-src="jp-valery.jpg" ci-ratio="1.5" />
    <img ci-src="kira-laktionov.jpg" ci-ratio="1.5" />  -->

    <!-- To add the lazyload library
    <script>
      window.lazySizesConfig = window.lazySizesConfig || {};
      window.lazySizesConfig.init = false;
    </script>
    <script src="https://cdn.scaleflex.it/filerobot/js-cloudimage-responsive/lazysizes.min.js"></script> -->

    <!-- To add the js-cloudimage-responsiv library -->
    <script src="https://cdn.scaleflex.it/plugins/js-cloudimage-responsive/4.5.0/js-cloudimage-responsive.min.js"></script>

    <!-- To initialize cloudimage responsive plugin -->
    <script>
      var cloudimgResponsive = new window.CIResponsive({
        token: "agnezucdmq",
        baseUrl: "https://digital.edufrem.com/wp-content/uploads/2022/01/",
        lazyLoading: true,
        queryString: '?size_info=1'
      });
      window.lazySizes.init();
    </script>
  </body>
</html>
