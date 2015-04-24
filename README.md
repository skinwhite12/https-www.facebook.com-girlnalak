# https-www.facebook.com-girlnalak
&lt;script>   window.fbAsyncInit = function() {     FB.init({       appId      : '586124978176225',       xfbml      : true,       version    : 'v2.3'     });      // ADD ADDITIONAL FACEBOOK CODE HERE   };    (function(d, s, id){      var js, fjs = d.getElementsByTagName(s)[0];      if (d.getElementById(id)) {return;}      js = d.createElement(s); js.id = id;      js.src = "//connect.facebook.net/en_US/sdk.js";      fjs.parentNode.insertBefore(js, fjs);    }(document, 'script', 'facebook-jssdk')); &lt;/script>
<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId      : '586124978176225',
      xfbml      : true,
      version    : 'v2.3'
    });

    // ADD ADDITIONAL FACEBOOK CODE HERE
  };

  (function(d, s, id){
     var js, fjs = d.getElementsByTagName(s)[0];
     if (d.getElementById(id)) {return;}
     js = d.createElement(s); js.id = id;
     js.src = "//connect.facebook.net/en_US/sdk.js";
     fjs.parentNode.insertBefore(js, fjs);
   }(document, 'script', 'facebook-jssdk'));
</script>
<h1 id="fb-welcome"></h1>
// Place following code after FB.init call.

function onLogin(response) {
  if (response.status == 'connected') {
    FB.api('/me?fields=first_name', function(data) {
      var welcomeBlock = document.getElementById('fb-welcome');
      welcomeBlock.innerHTML = 'Hello, ' + data.first_name + '!';
    });
  }
}

Fdiv id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/th_TH/sdk.js#xfbml=1&version=v2.3&appId=686173218139684";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
<div class="fb-like" data-href="https://www.facebook.com/girlnalak/docs/plugins/" data-layout="standard" data-action="like" data-show-faces="true" data-share="true"></div>
