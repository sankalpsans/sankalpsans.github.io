<html>
   <head>
   <meta charset="utf-8">
      <title>Facebook Love button demo</title>
	  <style>
        body {
            width: 500px;
            margin: 0 auto;
        }
        
        .love {
            margin-top: 10px;
            position: absolute;
            display: block;
            float: left;
            background: #de2a85;
            height: 20px;
            width: 20px;
            font-size: 12px;
            text-align: center;
            line-height: 20px;
            border-radius: 10px;
            color: #fff;
            cursor: pointer;
            transition: all .2s;
        }
        
        .love:hover {
            transform: scale(1.2);
        }
        .hem {
            margin-top: 10px;
            margin-left: 20px;
            position: absolute;
            display: block;
            float: left;
            background: #132;
            height: 20px;
            width: 20px;
            font-size: 12px;
            text-align: center;
            line-height: 20px;
            border-radius: 10px;
            color: #fff;
            cursor: pointer;
            transition: all .2s;
        }
        
        .hem:hover {
            transform: scale(1.2);
        }
        
        .one-post {
            background: #ddd;
            width: 100%;
            height: 200px;
        }
    </style>
   </head>
   <body>
   <div class="holder">
        <div class="one-post">
        </div>
        <div class="heart-holder">
            <span class="love">♥</span>
        </div>
        <div class="hem-holder">
            <span class="hem">H</span>
        </div>
    </div>
   </body>
   <script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-69404210-1', 'auto');
  ga('send', 'pageview');

</script>
</html>
