<html>
   <head>
      <title>Halfstyle Demo</title>
      <link rel="stylesheet" href="https://rawgit.com/sankalpsans/HalfStyle/master/css/halfstyle.css" />
      <script type="text/javascript" src = "https://rawgit.com/sankalpsans/HalfStyle/master/js/halfstyle.js"></script>
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
   <script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-69404210-1', 'auto');
  ga('send', 'pageview');

</script>
</html>
