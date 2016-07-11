<html>
   <head>
      <title>css-snake</title>
   </head>
   <body>
      <p>
		On GitHub <a href="http://github.com/arbelh/HalfStyle">http://github.com/arbelh/HalfStyle</a>
	</p>
	<hr/>
	<p>
		For the automated mode, just add the class <code>.textToHalfStyle</code> and the data attribute <code>data-halfstyle="[-CustomClassName-]"</code> to the element containing the text. The included jQuery snippet will do the rest of the job.
		<br/>
		You can have a look at the included demo.html file's source if you need to see example codes.
	</p>
	<hr/>
	<h3>Base Solution</h3>
	<h4>class: <code>hs-base</code></h4>
	<p>Single Characters: (Pure CSS, no Javascript)</p>
	<span class="halfStyle hs-base" data-content="X">X</span>
	<span class="halfStyle hs-base" data-content="Y">Y</span>
	<span class="halfStyle hs-base" data-content="Z">Z</span>
	<span class="halfStyle hs-base" data-content="A">A</span>
	<hr/>
	<p>Automated on any text: (Requires jQuery to automate the task)</p>
	<span class="textToHalfStyle" data-halfstyle="hs-base">Half-style, please.</span>
	<hr/>
	<h3>Vertical Half</h3>
	<h4>class: <code>hs-vertical-half</code></h4>
	<p>Single Characters:</p>
	<span class="halfStyle hs-vertical-half" data-content="X">X</span>
	<span class="halfStyle hs-vertical-half" data-content="Y">Y</span>
	<span class="halfStyle hs-vertical-half" data-content="Z">Z</span>
	<span class="halfStyle hs-vertical-half" data-content="A">A</span>
	<hr/>
	<p>Automated on any text:</p>
	<span class="textToHalfStyle" data-halfstyle="hs-vertical-half">Half-style, please.</span>
	<hr/>
	<h3>Vertical 1/3</h3>
	<h4>class: <code>hs-vertical-third</code></h4>
	<p>Single Characters:</p>
	<span class="halfStyle hs-vertical-third" data-content="X">X</span>
	<span class="halfStyle hs-vertical-third" data-content="Y">Y</span>
	<span class="halfStyle hs-vertical-third" data-content="Z">Z</span>
	<span class="halfStyle hs-vertical-third" data-content="A">A</span>
	<hr/>
	<p>Automated on any text:</p>
	<span class="textToHalfStyle" data-halfstyle="hs-vertical-third">Half-style, please.</span>
	<hr/>
	<h3>Horizontal Half</h3>
	<h4>class: <code>hs-horizontal-half</code></h4>
	<p>Single Characters:</p>
	<span class="halfStyle hs-horizontal-half" data-content="X">X</span>
	<span class="halfStyle hs-horizontal-half" data-content="Y">Y</span>
	<span class="halfStyle hs-horizontal-half" data-content="Z">Z</span>
	<span class="halfStyle hs-horizontal-half" data-content="A">A</span>
	<hr/>
	<p>Automated on any text:</p>
	<span class="textToHalfStyle" data-halfstyle="hs-horizontal-half">Half-style, please.</span>
	<hr/>
	<h3>Horizontal 1/3</h3>
	<h4>class: <code>hs-horizontal-third</code></h4>
	<p>Single Characters:</p>
	<span class="halfStyle hs-horizontal-third" data-content="X">X</span>
	<span class="halfStyle hs-horizontal-third" data-content="Y">Y</span>
	<span class="halfStyle hs-horizontal-third" data-content="Z">Z</span>
	<span class="halfStyle hs-horizontal-third" data-content="A">A</span>
	<hr/>
	<p>Automated on any text:</p>
	<span class="textToHalfStyle" data-halfstyle="hs-horizontal-third">Half-style, please.</span>
	<hr/>
	<h3>PeelingStyle by user SamTremaine on StackOverflow.com
	<br/>Also available on <a href="http://experimental.samtremaine.co.uk/half-style/">http://experimental.samtremaine.co.uk/half-style/</a></h3>
	<h4>class: <code>hs-PeelingStyle</code></h4>
	<p>Single Characters:</p>
	<span class="halfStyle hs-PeelingStyle" data-content="X">X</span>
	<span class="halfStyle hs-PeelingStyle" data-content="Y">Y</span>
	<span class="halfStyle hs-PeelingStyle" data-content="Z">Z</span>
	<span class="halfStyle hs-PeelingStyle" data-content="A">A</span>
	<hr/>
	<p>Automated on any text:</p>
	<span class="textToHalfStyle" data-halfstyle="hs-PeelingStyle">Half-style, please.</span>
	<hr/>
	<h3>KevinGranger - By user KevinGranger on StackOverflow.com
	<br/>Reqires black background and an external font for the best looks, see a full demo at <a href="http://jsfiddle.net/Kevin_Granger/pd9yB/327/">http://jsfiddle.net/Kevin_Granger/pd9yB/327/</a></h3>
	<h4>class: <code>hs-KevinGranger</code></h4>
	<div style="background-color:black">
		<p>Single Characters:</p>
		<span class="halfStyle hs-KevinGranger" data-content="X">X</span>
		<span class="halfStyle hs-KevinGranger" data-content="Y">Y</span>
		<span class="halfStyle hs-KevinGranger" data-content="Z">Z</span>
		<span class="halfStyle hs-KevinGranger" data-content="A">A</span>
		<hr/>
		<p>Automated on any text:</p>
		<span class="textToHalfStyle" data-halfstyle="hs-KevinGranger">Half-style, please.</span>
	</div>
	<p>
		On GitHub <a href="http://github.com/arbelh/HalfStyle">http://github.com/arbelh/HalfStyle</a>
	</p>
   </body>
   <style type="text/css">
      body{ padding:0;margin:0;background: #FFF;color: #777; float: left; font-family: sans-serif; }
      #board{ float: left;width:600px;height:600px;background: #757575; }
      .pixel{ width:10px;height:10px;float: left;background:transparent; }
      .pixel-lighted{background:#fff;}
      .caption{padding: 5px; font-size:48px;}
      .sub-caption{font-size: 14px; color: #bbb; padding: 10px 6px 30px;}
   </style>
   <script type="text/javascript">
     /*!
 * HalfStyle
 * Copyright 2014 Arbel Hakopian
 * Licensed under MIT (https://github.com/arbelh/HalfStyle/blob/master/license.md)
 */
window.onload = function(){ initHalfStyle(); };
function initHalfStyle() {
    var halfstyle_text, halfstyle_chars, $halfstyle_el, halfstyle_i, halfstyle_output, halfstyle_style;

    // Iterate over all class occurrences
    var domsToIterate = document.getElementsByClassName('textToHalfStyle');
    for(var i = 0; i < domsToIterate.length; i = i + 1) {
        halfstyle_el = domsToIterate[i];
        halfstyle_style = halfstyle_el.attributes['data-halfstyle'].value;
        halfstyle_text = halfstyle_el.innerText;
        halfstyle_chars = halfstyle_text.split('');

        // Set the screen-reader text
	halfstyle_output = '<span style="position: absolute !important;clip: rect(1px 1px 1px 1px);clip: rect(1px, 1px, 1px, 1px);">' + halfstyle_text + '</span>';

        // Iterate over all chars in the text
        for (halfstyle_i = 0; halfstyle_i < halfstyle_chars.length; halfstyle_i++) {
            // Create a styled element for each character and append to container
            halfstyle_output += '<span aria-hidden="true" class="halfStyle ' + halfstyle_style + '" data-content="' + halfstyle_chars[halfstyle_i] + '">' + halfstyle_chars[halfstyle_i] + '</span>';
        }
	halfstyle_el.innerHTML = halfstyle_output;
    }
};
   </script>
   <script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-69404210-1', 'auto');
  ga('send', 'pageview');

</script>
</html>
