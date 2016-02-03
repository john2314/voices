# voices
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        
            <title>Free Online Frequency Sweep Generator | OnlineToneGenerator.com</title>
        
        <meta name="viewport" content="initial-scale=1">

        

        <link rel="shortcut icon" type="image/png" href="/favicon.png">

        <link href="/css/main.css?v=3" rel="stylesheet" type="text/css">

        <script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>

    </head>

    <body>
    	<div id="wrapper"  >



        <div id="navMenu">
            <ul id="nav" class=''>
        <li><a href="#" class="js-menu-toggle">&#9776; Show menu</a></li>
        
            <li class=" ">
                <a class="" href="/">Home </a>
            </li>
            <li class=" ">
                <a class="" href="/pitch-shifter.html">Pitch Shifter </a>
            </li>
            <li class=" ">
                <a class="" href="/time-stretcher.html">Time Stretcher <span class='new'>NEW</span></a>
            </li>
            <li class=" ">
                <a class="" href="/voice-generator.html">Voice Generator </a>
            </li>
            <li class="current ">
                <a class="current" href="/frequency-sweep-generator.html">Sweep Generator </a>
            </li>
            <li class=" ">
                <a class="" href="/tuning.html">Instrument Tuning </a>
            </li>
            <li class=" ">
                <a class="" href="/subwoofer.html">Subwoofer Testing </a>
            </li>
            <li class=" ">
                <a class="" href="/hearingtest.html">Hearing Test </a>
            </li>
            <li class=" ">
                <a class="" href="/noise.html">Noise Generator </a>
            </li>
            <li class=" ">
                <a class="" href="/binauralbeats.html">Binaural Beats </a>
            </li>
            <li class=" ">
                <a class="" href="/432Hz.html">432Hz Frequency </a>
            </li>
            <li class=" ">
                <a class="" href="/dtmf.html">DTMF Signals </a>
            </li>
            <li class=" ">
                <a class="" href="/pips.html">The Pips </a>
            </li>
            <li class=" ">
                <a class="" href="/theory.html">Acoustic Theory </a>
            </li>
            <li class=" last">
                <a class="" href="/about.html">About </a>
            </li>
        

</ul>

<div class="iframe-wrapper" id='amazon-wrapper'>
<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src=''></iframe>
</div>

    
<script>

    $("#amazon-wrapper iframe").attr("src", function(){
        var srcs = ["//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=onlitonegene-20&marketplace=amazon&region=US&placement=B00K6CX3MO&asins=B00K6CX3MO&linkId=NEWHD3WDVKT2VKR5&show_border=true&link_opens_in_new_window=true&price_color=27A159&title_color=0066C0&bg_color=FFFFFF",
            "//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=onlitonegene-20&marketplace=amazon&region=US&placement=B004M8UZS8&asins=B004M8UZS8&linkId=UA3S6OIXAOJMPH3F&show_border=true&link_opens_in_new_window=true&price_color=27A159&title_color=0066C0&bg_color=FFFFFF",
            "//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=onlitonegene-20&marketplace=amazon&region=US&placement=B00WK47VEW&asins=B00WK47VEW&linkId=7LEBKY765ADLYRNI&show_border=true&link_opens_in_new_window=true&price_color=27A159&title_color=0066C0&bg_color=FFFFFF",
            "//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=onlitonegene-20&marketplace=amazon&region=US&placement=B0070U8KSM&asins=B0070U8KSM&linkId=KMSKNV3B2EYCNTIX&show_border=true&link_opens_in_new_window=true&&price_color=27A159&title_color=0066C0&bg_color=FFFFFF",
            "//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=onlitonegene-20&marketplace=amazon&region=US&placement=B006HCQZDQ&asins=B006HCQZDQ&linkId=XE56EMXTDCCJHNQQ&show_border=true&link_opens_in_new_window=true&price_color=27A159&title_color=0066C0&bg_color=FFFFFF",
            "//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=onlitonegene-20&marketplace=amazon&region=US&placement=B00B5SKWBS&asins=B00B5SKWBS&linkId=PIY74OWTXMFMWMC4&show_border=true&link_opens_in_new_window=true&price_color=27A159&title_color=0066C0&bg_color=FFFFFF"
        ]
        var min = 0;
        var max = srcs.length - 1;
        var rand = Math.floor(Math.random()*(max-min+1)+min);
        return srcs[rand];
        
    });

    $(".js-menu-toggle").click(function(e){
        e.preventDefault();
        $nav = $(this).parents("#nav");
        if ($nav.hasClass("js-open")){
            // $nav.height($(this).outerHeight());
            $(this).html("&#9776; Show menu");
        } else {
            // $nav.height("auto");
            $(this).html("&#9776; Close menu");
        }
        $nav.toggleClass("js-open");
    });
</script>
        </div>

    		<div id="mainContent">

          <h1><a href='/'><!-- <img src="/img/Speaker_Icon-tilted.png" alt=""> -->Online Tone Generator</a></h1>
          <p class="tagline"><strong>Free online frequency sweep generator.</strong></p>

		  <p>
	This frequency sweep tool allows you to enter any two frequencies and a duration into the three boxes below. Once the play button is pressed, the frequency sweeper will then
	play a tone that begins at the first frequency and sweeps to the second frequency in the duration provided.
</p>

<p>
	The sweep generator tool also enables you to set some more advanced options. You can choose the waveform to be either: sine, square, sawtooth or triangle.
	There is also an option to determine whether the sweep is done linearly (equal frequency changes over equal time intervals), or exponentially (higher frequencies are swept over
	more quickly). If you wish the tone to continue playing after the sweep is complete, leave the "continue playing tone" option checked, otherwise click it to turn this feature off.
	Finally, the sweep generator allows you to set an start volume and end volume. These are numbers between 1 and 100, with 1 being the quietest and 100 being the loudest. (If you do not require this functionality, you can simply leave these boxes at their default setting, which will produce an equal volume sweep.)
</p>

<p>
	Please be very careful using this tool as listening to loud frequencies can cause damage to hearing or equipment. Please only listen at a comfortable volume.
	Please note, as this is very new technology, the frequency sweep generator is currently only compatible with the latest version of Chrome or Safari and Firefox. Internet Explorer is not currently supported.
</p>



<div class="generator-ad-wrapper">
<div class="frequency-sweeper">

		<div class="frequency-options-wrapper">
		<div class="input-group">
			<p>Start frequency<br />(in Hz)<br />
			<input type="text" class="input--frequency-start" id="freq-start" name="freq-start" value="1">
			</p>
		</div>

		<div class="input-group">
			<p>End frequency<br />(in Hz)<br />
			<input type="text" class="input--frequency-end" id="freq-end" name="freq-end" value="1000">
			</p>
		</div>

		<div class="input-group">
			<p>Duration<br />(in seconds)<br />
			<input type="text" class="input--duration" id="duration" name="duration" value="10">
			</p>
		</div>
		</div>

	    <div class="advanced-options">
	    	<div class="waveform-wrapper">
		    	<input type="radio" name="waveform" value='sine' id='sine' checked>
		    	<label for="sine">Sine</label>
		    	<div class="waveform-image waveform-image--sine"></div>
	    	</div>
	    	<div class="waveform-wrapper">
		    	<input type="radio" name="waveform" value='square' id='square'>
		    	<label for="square">Square</label>
		    	<div class="waveform-image waveform-image--square"></div>
	    	</div>
	    	<div class="waveform-wrapper">
		    	<input type="radio" name="waveform" value='sawtooth' id='sawtooth'>
		    	<label for="sawtooth">Sawtooth</label>
		    	<div class="waveform-image waveform-image--sawtooth"></div>
	    	</div>
	    	<div class="waveform-wrapper">
		    	<input type="radio" name="waveform" value='triangle' id='triangle'>
		    	<label for="triangle">Triangle</label>
		    	<div class="waveform-image waveform-image--triangle"></div>
	    	</div>
	    </div>

    <div class="clear"></div>

	<p>
	<label for="ramp-type-linear">
		Linear sweep
		<input id='ramp-type-linear' type="radio" checked name='ramp' value='linear'>
	</label>
	<label for="ramp-type-exponential">
		Exponential sweep
		<input id='ramp-type-exponential' type="radio" name='ramp' value='exp'>
	</label>
	<br />
	<label for="maintain-tone">Continue playing tone after sweep has finished? <input id='maintain-tone' type="checkbox" checked value='1'></label>
	</p>

	<p>
		<label for="start-volume">
			Start Volume:
			<input id='start-volume' type="text" value='40'>
		</label><br />
		<label for="end-volume">
			End Volume:
			<input id='end-volume' type="text" value='40'>
		</label>
	</p>

	<p>
		Current Frequency: <span id='current-frequency'>1</span>Hz<br />
		Current Time: <span id='current-time'>0</span>s<br />
		Current Volume: <span id='current-volume'>40</span>%<br />
	</p>


	<div class="generator-buttons">
	    <button type="button" class="beginTuning generatorButton">Play</button>
	    <button type="button" class="stopTuning generatorButton" onclick="stop()">Stop</button>
    </div>

</div>
<div class="rectangle-ad-wrapper" >
	
	<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
	<!-- Rectangle Ad -->
	<ins class="adsbygoogle"
	     style="display:inline-block;width:300px;height:250px"
	     data-ad-client="ca-pub-1442085105034408"
	     data-ad-slot="1137156943"></ins>
	<script>
	(adsbygoogle = window.adsbygoogle || []).push({});
	</script>
	  
</div>

</div>

<script src='/js/frequency-sweeper.js'></script>

<div id="fb-root"></div>
<script>

$(window).on("load", function() {
	faceyb(document, 'script', 'facebook-jssdk');
	twitter(document, 'script', 'twitter-wjs');
});

function faceyb(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v2.0";
  fjs.parentNode.insertBefore(js, fjs);
};

function twitter(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}

/* Twitter */


</script>

<div class="social-buttons">
	<div class="twitter-share-button">
		<a href="https://twitter.com/share" data-url='http://onlinetonegenerator.com/frequency-sweep-generator.html' class="twitter-share-button"></a>
	</div>
	<div class="fb-share-button-wrapper">
		<div class="fb-share-button" data-href="http://onlinetonegenerator.com/frequency-sweep-generator.html" data-type="button_count"></div>
	</div>
</div>



<div class="ad-wrapper">
	
	 <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
	  <!-- Responsive ad for OTG header -->
	<ins class="adsbygoogle"
	       style="display:block"
	       data-ad-client="ca-pub-1442085105034408"
	       data-ad-slot="9656907346"
	       data-ad-format="horizontal"></ins>
	  <script>
		(adsbygoogle = window.adsbygoogle || []).push({});
	  </script>
	  
</div>

<div id="comments">
    <div id="disqus_thread"></div>
    <script type="text/javascript">
      var disqus_title = 'Frequency Sweep Generator';
    </script>
    <script type="text/javascript">
        /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
        var disqus_shortname = 'onlinetonegenerator';
    	var disqus_developer = 0;

        /* * * DON'T EDIT BELOW THIS LINE * * */
        (function() {
            var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
            dsq.src = 'http://' + disqus_shortname + '.disqus.com/embed.js';
            (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
    <a href="http://disqus.com" class="dsq-brlink">blog comments powered by <span class="logo-disqus">Disqus</span></a>

    <script type="text/javascript">
        /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
        var disqus_shortname = 'onlinetonegenerator'; // required: replace example with your forum shortname

        /* * * DON'T EDIT BELOW THIS LINE * * */
        (function () {
            var s = document.createElement('script'); s.async = true;
            s.type = 'text/javascript';
            s.src = 'http://' + disqus_shortname + '.disqus.com/count.js';
            (document.getElementsByTagName('HEAD')[0] || document.getElementsByTagName('BODY')[0]).appendChild(s);
        }());
    </script>
</div>

        </div>





        <div id="footer">
            Online Tone Generator utilises HTML5 and the Web Audio API. It is optimized for use with the latest versions of Chrome, Safari, Firefox and Microsoft Edge.

            <br />
            &copy;  2011 - 2015 onlinetonegenerator.com
        </div>

        <p style="clear:both"></p>

      </div>

        
        <script>


          (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
          (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
          m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
          })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

      if (window.location.host != 'localhost:4000') {
          ga('create', 'UA-17960919-2', 'onlinetonegenerator.com');
          ga('send', 'pageview');

          window.onerror = function(message, file, line){
            ga('send', 'event', 'JavaScript Error', message, file + ": Line "+ line, { 'nonInteraction': 1 });
          }

        }

        </script>

    </body>
</html>
