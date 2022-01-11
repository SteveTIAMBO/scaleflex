<!DOCTYPE html>
<html>
  <head>
    <title>JS Cloudimage Responsive Example with lazy load</title>
    <meta charset="UTF-8" />
  </head>

  <body>
    <h2>Steve's JS Cloudimage Responsive Demonstration</h2>

    <!-- adding my image image -->
    <img src="https://digital.edufrem.com/wp-content/uploads/2022/01/juice-bar-69.jpg" /></br>
    <img src="https://digital.edufrem.com/wp-content/uploads/2022/01/5.png" /></br>
    <img src="https://digital.edufrem.com/wp-content/uploads/2022/01/2.png" /></br>
    <img src="https://digital.edufrem.com/wp-content/uploads/2022/01/juice-bar-10.jpg" /></br>
    <img src="https://digital.edufrem.com/wp-content/uploads/2022/01/image-1.png" /></br>
    <img src="https://digital.edufrem.com/wp-content/uploads/2022/01/juice-bar-57.jpg"/>
    
    <!-- Change src to ci-src for your image 
    <img ci-src="alain.jpg" ci-ratio="1.5" /></br>
    <img ci-src="ameen-fahmy.jpg" ci-ratio="1.5" /></br>
    <img ci-src="tim-patch.jpg" ci-ratio="1.5" /></br>
    <img ci-src="veeterzy.jpg" ci-ratio="1.5" /></br>
    <img ci-src="dino-reichmuth.jpg" ci-ratio="1.5" /></br>
    <img ci-src="inma-lesielle.jpg" ci-ratio="1.5" />    -->

    <!-- Add lazyload library 
    <script>
      window.lazySizesConfig = window.lazySizesConfig || {};
      window.lazySizesConfig.init = false;
    </script>
    <script src="https://cdn.scaleflex.it/filerobot/js-cloudimage-responsive/lazysizes.min.js"></script> -->

    <!-- Add js-cloudimage-responsiv library 
    <script src="https://cdn.scaleflex.it/plugins/js-cloudimage-responsive/4.5.0/js-cloudimage-responsive.min.js"></script> -->

    <!-- Initialize cloudimage responsive 
    <script>
      var cloudimgResponsive = new window.CIResponsive({
        token: "demo",
        baseUrl: "https://cloudimage.public.airstore.io/demo/",
        lazyLoading: true,
        queryString: '?size_info=1'
      });
      window.lazySizes.init();
    </script> -->
  </body>
</html>
