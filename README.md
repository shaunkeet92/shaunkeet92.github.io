<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
    <script src="https://www.tiktok.com/felix/navigation/tiktokweb.js"></script>
  </head>
  <body>
    <h1>Welcome to my website!</h1>
    <p>Here's some content for my website.</p>
    <script>
      // TikTok Pixel Code
      !function(w,i,d,g,e,t){d.getElementById(e)||(t=d.createElement(g),t.id=e,t.src="https://analytics.tiktok.com/i18n/pixel/sdk.js?sdkid=XXXXXX&event=ViewContent",t.async=!0,(d.head||d.body).appendChild(t)),w.tiktoksdk||(w.tiktoksdk=new TiktokSdk(i,tiktoksdk),tiktoksdk.load({defaultEvent:"ViewContent"}))}(window,"TiktokSdk",document,"script","tiktok-js-sdk");
    </script>
  </body>
</html>
