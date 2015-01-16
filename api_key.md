---
layout: default
title: API Key
permalink: /api_key/
---

## API Key

{% raw %}
<div id="apidatagov_signup">Loading signup form...</div>
<script type="text/javascript">

 <!-- https://api.data.gov/gsa/auctions?api_key={{api_key}}&format=JSON -->

 /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
 var apiUmbrellaSignupOptions = {
   // Pick a short, unique name to identify your site, like 'gsa-auctions'
   // in this example.
   registrationSource: '3dpx_api',

   // Enter the API key you signed up for and specially configured for this
   // API key signup embed form.
   apiKey: 'dnxBeHGIXhCjPi9SesmB09I6n3GDYgWCuszutq0p',

   // Provide an example URL you want to show to users after they signup.
   // This can be any API endpoint on your server, and you can use the
   // special {{api_key}} variable to automatically substitute in the API
   // key the user just signed up for.
   exampleApiUrl: 'http://api.data.gov/nih/3dprint/model/1.0/model_single.json?model_id=000914&api_key={{api_key}}'
 };

 /* * * DON'T EDIT BELOW THIS LINE * * */
 (function() {
   var apiUmbrella = document.createElement('script'); apiUmbrella.type = 'text/javascript'; apiUmbrella.async = true;
   apiUmbrella.src = 'https://api.data.gov/static/javascripts/signup_embed.js';
   (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(apiUmbrella);
 })();
</script>
<noscript>Please enable JavaScript to signup for an <a href="http://api.data.gov/">api.data.gov</a> API key.</noscript> 
{% endraw %}



