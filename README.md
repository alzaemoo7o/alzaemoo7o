{
  "short_name": "Weather",
  "name": "Weather: Do I need an umbrella?",
  "description": "Weather forecast information",
  "icons": [
    {
      "src": "/images/icons-192.png",
      "type": "image/png",
      "sizes": "192x192"
    },
    {
      "src": "/images/icons-512.png",
      "type": "image/png",
      "sizes": "512x512"
    }
  ],
  "start_url": "/?source=pwa",
  "background_color": "#3367D6",
  "display": "standalone",
  "scope": "/",
  "theme_color": "#3367D6",
  "shortcuts": [
    {
      "name": "How's weather today?",
      "short_name": "Today",
      "description": "View weather information for today",
      "url": "/today?source=pwa",
      "icons": [{ "src": "/images/today.png", "sizes": "192x192" }]
    },
    {
      "name": "How's weather tomorrow?",
      "short_name": "Tomorrow",
      "description": "View weather information for tomorrow",
      "url": "/tomorrow?source=pwa",
      "icons": [{ "src": "/images/tomorrow.png", "sizes": "192x192" }]
    }
  ]
}{
  "short_name": "Weather",
  "name": "Weather: Do I need an umbrella?",
  "description": "Weather forecast information",
  "icons": [
    {
      "src": "/images/icons-192.png",
      "type": "image/png",
      "sizes": "192x192"
    },
    {
      "src": "/images/icons-512.png",
      "type": "image/png",
      "sizes": "512x512"
    }
  ],
  "start_url": "/?source=pwa",
  "background_color": "#3367D6",
  "display": "standalone",
  "scope": "/",
  "theme_color": "#3367D6",
  "shortcuts": [
    {
      "name": "How's weather today?",
      "short_name": "Today",
      "description": "View weather information for today",
      "url": "/today?source=pwa",
      "icons": [{ "src": "/images/today.png", "sizes": "192x192" }]
    },
    {
      "name": "How's weather tomorrow?",
      "short_name": "Tomorrow",
      "description": "View weather information for tomorrow",
      "url": "/tomorrow?source=pwa",
      "icons": [{ "src": "/images/tomorrow.png", "sizes": "192x192" }]
    }
  ]
}
 ⚡ lang="ar">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
    <meta name="description" content="This is the AMP Boilerplate.">
    <link rel="preload" as="script" href="https://cdn.ampproject.org/v0.js">
    <link rel="preload" as="script" href="https://cdn.ampproject.org/v0/amp-dynamic-css-classes-0.1.js">
    <link rel="preload" href="hero-img.jpg" as="image">
    <link rel="preload" href="poster.jpg" as="image">
    <link rel="preconnect dns-prefetch" href="https://fonts.gstatic.com/" crossorigin>
    <script async src="https://cdn.ampproject.org/v0.js"></script>
    <script async custom-element="amp-dynamic-css-classes" src="https://cdn.ampproject.org/v0/amp-dynamic-css-classes-0.1.js"></script>
    <!-- Import other AMP Extensions here -->
    <script async custom-element="amp-video" src="https://cdn.ampproject.org/v0/amp-video-0.1.js"></script>
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
    <style amp-custom>
    /* Add your styles here */
    </style>
    <style amp-boilerplate>body{-webkit-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-moz-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-ms-animation:-amp-start 8s steps(1,end) 0s 1 normal both;animation:-amp-start 8s steps(1,end) 0s 1 normal both}@-webkit-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-moz-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-ms-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-o-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}</style><noscript><style amp-boilerplate>body{-webkit-animation:none;-moz-animation:none;-ms-animation:none;animation:none}</style></noscript>

    <link rel="canonical" href=".">
    <title>My AMP Page</title>
    <link rel="manifest" href="/manifest.json">
    <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "Webpage",
      "url": "https://www.example.com",
      "name": "My Webpage",
      "headline": "webpage title",
      "description": "Here is the description",
      "mainEntityOfPage": {
        "@type": "WebPage",
        "@id": "https://www.example.com"
      },
      "publisher": {
        "@type": "Organization",
        "name": "The Publisher",
        "logo": {
          "url": "https://www.example.com/logo-blue.svg",
          "width": 175,
          "height": 60,
          "@type": "ImageObject"
        }
      },
      "image": {
        "@type": "ImageObject",
        "url": "https://www.example.com/leader.png",
        "width": 1200,
        "height": 630
      }
    }
    </script>
  </head>
  <body>
    <h1>Hello World</h1>
    <amp-img src="hero-img.jpg"
             width="1280" 
             height="720"
             layout="responsive" 
             alt="This is a hero image which should be loaded as fast as possible">
    </amp-img>
    <amp-video width="640"
               height="360"
               layout="responsive"
               poster="poster.jpg"
               artwork="artwork.png"
               title="My video"
               artist="The artist"
               album="The album">
      <source src="video.m3u8" type="application/vnd.apple.mpegurl">
      <source src="video.mp4" type="video/mp4">
      <div fallback>This browser does not support the video element.</div>
    </amp-video>
    <amp-analytics>
      <script type="application/json">
      {
        "transport": {
          "xhrpost": false,
          "beacon": true
        },
        "requests": {
          "base": "https://${trackingServer}/b/ss/${accounts}/1/AMP-0.1/s${random}",
          "pageView": "${base}?AQB=1&vid=CLIENT_ID(adobe_amp_id)&pageName=${pageName}&j=amp&AQE=1",
          "buttonClick": "${base}?AQB=1&vid=CLIENT_ID(adobe_amp_id)&pageName=${pageName}&j=amp&pe=lnk_o&v1=${eVar1}&AQE=1"
        },
        "vars": {
          "trackingServer": "metrics.example.com",
          "accounts": "reportSuiteID",
          "pageName": "Adobe Analytics Using amp-analytics tag"
        },
        "triggers": {
          "pageLoad": {
            "on": "visible",
            "request": "pageView"
          },
          "click": {
            "on": "click",
            "selector": "button",
            "request": "buttonClick",
            "vars": {
              "eVar1": "button clicked"
            }
          }
        }
      }
      </script>
    </amp-analytics> 
  </body>
</html>
