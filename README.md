# include-local-jquery-if-CDN-is-Down-
include local jquery if "CDN is Down" 

<code> &lt;script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"&gt; &lt;/script&gt;
 &lt;script&gt;
 window.jquery || document.write('&lt;script src="jquery.js"&gt;&lt;/script&gt;')
 &lt;/script&gt;
 </code>
