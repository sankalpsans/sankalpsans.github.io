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
        .grey-btn{
            position: fixed; bottom: 5px; border-radius: 3px; background: #ddd;
            color: #333; font-family: sans-serif; padding: 3px 7px; font-size: 12px; text-decoration: none;
        }
        .grey-btn:hover{
            background:#eee;
        }

        .src-btn{
            position: absolute;margin-left: 100px;margin-top: 13px;
    background: #4791da;
    color: #fff;
    font-family: sans-serif;
    text-decoration: none;
    padding: 3px 8px;
    font-size: 12px;
    border-radius: 3px;
    font-weight: bold;
    border-bottom: solid 2px #3573af;
        }
        .src-btn:hover{
            background:#64a7e8;
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
    <div>
    <a class="grey-btn" href="https://github.com/sankalpsans">← Back to github profile</a>
    <a class="src-btn" href="https://github.com/sankalpsans/fb-peace-button">View source</a>
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
<script>
            var numberOfHearts = 40;
            var varianceInSize = 3;
            var delay = 200; //milliseconds
            var length = -200;
            HTMLElement.prototype.multiply = function() {
                var domToClone = this;
                this.style.zIndex = "2";
                this.addEventListener("click", function explode() {
                    
                    for(var i = 0; i < numberOfHearts; i += 1) {
                        var newElement = this.cloneNode(true);
                        var completeStyle = window.getComputedStyle(this, null).cssText;
                        newElement.style.cssText = completeStyle;
                        var finalXTranslation = (Math.random() - .5)  * length; // So that all hearts toss evenly both left and right sides
                        var finalYTranslation = (Math.random() + .2) / 2 * length;
                        var angle = Math.atan(finalYTranslation / finalXTranslation) * (180 / Math.PI);
                        var scale = Math.random() * varianceInSize;
                        newElement.setAttribute("finalXTranslation", finalXTranslation);
                        newElement.setAttribute("finalYTranslation", finalYTranslation);
                        newElement.setAttribute("scale", scale);
                        newElement.style.zIndex="1";
                        newElement.style.transform = "rotate("+ angle +"deg) ";
                        this.parentNode.appendChild(newElement);
                    }
                    setTimeout(function() {
                        for(var i = 1; i < domToClone.parentNode.children.length; i += 1) {
                            var thisHeart = domToClone.parentNode.children[i];
                            thisHeart.style.transform = thisHeart.style.transform +
                            " scale(" + thisHeart.attributes.scale.value + ")"+
                            " translate("+thisHeart.attributes.finalXTranslation.value+"px, "+thisHeart.attributes.finalYTranslation.value+"px)";
                        }
                    }, delay);
                    setTimeout(function() {
                        for(var i = 1; i < domToClone.parentNode.children.length; i += 1) {
                            var thisHeart = domToClone.parentNode.children[i];
                            thisHeart.style.transition = "all "+(Math.random() * 2)+"s";
                            thisHeart.style.opacity = "0";
                        }
                    }, delay);
                    
                });
            }
            document.querySelector('.love').multiply();
            document.querySelector('.hem').multiply();
            </script>
</html>
