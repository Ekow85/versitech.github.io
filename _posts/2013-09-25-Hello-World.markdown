---
layout: post
title: H3110 W0R1D !
category: Coding
tags: bootstrap github fuelux jekyll 
year: 2013
month: 9
day: 25
published: true
summary: Every hack has to say hello to everyone right ?
image: post_one.png
---

<div class="row">	
	<div class="span9 columns">
	  <h2>OK</h2>
	  <p>Let me leave this with a John Whitlock quote on precisely the relevance of this post.</p>
	  <p><i>"Hello, World" doesn't teach much about the language, but it does teach something very important - the computer is a tool that you control. It was an <u>AhaMoment</u> for me, as I realized that I created an executable program, simplier but fundamentally the same as all those other programs I'd been running for years. I believe the first modification to this program is one of the most important - in my case, changing the message to "Hello, John!". Followed, of course, by an infinite loop saying "John is Great!" It is the moment where I ceased to be a mere computer user, and became a computer programmer.</i> -- John Whitlock</p>
	</div>
</div> 

<div class="row">	
	<div class="span9 column">
			<p class="pull-right">{% if page.previous.url %} <a href="{{page.previous.url}}" title="Previous Post: {{page.previous.title}}"><i class="icon-chevron-left"></i></a> 	{% endif %}   {% if page.next.url %} 	<a href="{{page.next.url}}" title="Next Post: {{page.next.title}}"><i class="icon-chevron-right"></i></a> 	{% endif %} </p>  
	</div>
</div>

<div class="row">	
    <div class="span9 columns">    
		<h2>Comments Section</h2>
	    <p>Feel free to comment on the post but keep it clean and on topic.</p>	
		<div id="disqus_thread"></div>
		<script type="text/javascript">
			/* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
			var disqus_shortname = 'ericjones'; // required: replace example with your forum shortname
			var disqus_identifier = '/blog/How-I-built-my-blog-in-one-day';
			var disqus_url = '/blog/How-I-built-my-blog-in-one-day';
			
			/* * * DON'T EDIT BELOW THIS LINE * * */
			(function() {
				var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
				dsq.src = 'http://' + disqus_shortname + '.disqus.com/embed.js';
				(document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
			})();
		</script>
		<noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
		<a href="http://disqus.com" class="dsq-brlink">blog comments powered by <span class="logo-disqus">Disqus</span></a>
	</div>
</div>

<!-- Twitter -->
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>

<!-- Google + -->
<script type="text/javascript">
  (function() {
    var po = document.createElement('script'); po.type = 'text/javascript'; po.async = true;
    po.src = 'https://apis.google.com/js/plusone.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(po, s);
  })();
</script>
