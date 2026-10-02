First Class Moving and Delivery - website
==========================================

Files
  index.html        The website (HTML, CSS and JavaScript in one file)
  images/van.webp   Hero photo
  images/logo.png   Header logo
  images/favicon.svg Browser tab icon
  robots.txt        Tells search engines they can crawl the site
  sitemap.xml       Page list for Google Search Console

Before going live
  1. Replace YOURDOMAIN.com in robots.txt and sitemap.xml with the real domain.
  2. In index.html <head>, add:
       <link rel="canonical" href="https://YOURDOMAIN.com/">
       <meta property="og:url" content="https://YOURDOMAIN.com/">
       <meta property="og:image" content="https://YOURDOMAIN.com/images/van.webp">
  3. Add Google Tag Manager in <head>. The site already sends these events to the dataLayer:
       call_click       (every phone link, with click_location)
       whatsapp_click   (every WhatsApp link and the quote form)
     Mark them as conversions in GA4 / Google Ads.
  4. Submit sitemap.xml in Google Search Console.

Hosting
  Upload the whole folder to any static host (Vercel, Netlify, Cloudflare Pages,
  Hostinger, cPanel public_html). No server or database needed.

Phone / WhatsApp number used everywhere: +1 647-804-4411
To change it, search index.html for 6478044411 and 647-804-4411.
