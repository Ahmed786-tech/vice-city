##Read Me
Watch Video: https://ezadtv.com/file/10807-f7df

Must Do Check-List
1. Make sure you have the following files:
    1. sitemaps.xml
    2. Robots.txt
    3. .htaccess
2. Any routes that you create or links to new pages you must update the .htaccess file, and make sure that all A Hrefs do not contain the .html extension
    ex: NO to "/sign-up.html", YES to "/sign-up"

3. Make sure all images do:
    1. Alt attribute is there
    2. convert all png & jpeg to WEBP format
    3. Make sure you use the EZ-Uploader on Kachooni to HOST all images: https://kachooni.com/admin:ezuploader/edit-email/-1
    4. Make sure that Images are not unnecessarily large, if they are then use a compression software or ask the dev team

4. Make sure that all css & js files have both mininified and raw files
    1. Make sure that all html files are using the minified files

5. Make sure that you have proper Meta Tags On the Page
    1. Convert Favicon to ico file
    2. Make sure you have main image src (if not ask the design team)
    3. Make sure to set the Title Tag & Description (if not provided then ASK!)
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <!-- Search Engine -->
        <meta name="description" content="Text blast your list with the cheapest sms marketing service. Looking for the lowest price and easiest to use platform? Try SaturnText now.">
        <meta name="image" content="https://storage.googleapis.com/content.ezadtv.com/2020/01/09/5e17eebba26fb_web_image.jpg">
        <!-- Schema.org for Google -->
        <meta itemprop="name" content="SaturnText">
        <meta itemprop="description" content="Text blast your list with the cheapest sms marketing service. Looking for the lowest price and easiest to use platform? Try SaturnText now.">
        <meta itemprop="image" content="https://storage.googleapis.com/content.ezadtv.com/2020/01/09/5e17eebba26fb_web_image.jpg">

        <meta name="og:url" content="https://saturntext.com">
        <meta name="og:type" content="website">

        <title>Simple & Affordable Text Blast Service For Your Business | SaturnText</title>

        <link rel="apple-touch-icon" sizes="57x57" href="/media/saturntext/logos/apple-icon-57x57.png">
        <link rel="apple-touch-icon" sizes="60x60" href="/media/saturntext/logos/apple-icon-60x60.png">
        <link rel="apple-touch-icon" sizes="72x72" href="/media/saturntext/logos/apple-icon-72x72.png">
        <link rel="apple-touch-icon" sizes="76x76" href="/media/saturntext/logos/apple-icon-76x76.png">
        <link rel="apple-touch-icon" sizes="114x114" href="/media/saturntext/logos/apple-icon-114x114.png">
        <link rel="apple-touch-icon" sizes="120x120" href="/media/saturntext/logos/apple-icon-120x120.png">
        <link rel="apple-touch-icon" sizes="144x144" href="/media/saturntext/logos/apple-icon-144x144.png">
        <link rel="apple-touch-icon" sizes="152x152" href="/media/saturntext/logos/apple-icon-152x152.png">
        <link rel="apple-touch-icon" sizes="180x180" href="/media/saturntext/logos/apple-icon-180x180.png">
        <link rel="icon" type="image/png" sizes="192x192"  href="/media/saturntext/logos/android-icon-192x192.png">
        <link rel="icon" type="image/png" sizes="32x32" href="/media/saturntext/logos/favicon-32x32.png">
        <link rel="icon" type="image/png" sizes="96x96" href="/media/saturntext/logos/favicon-96x96.png?">
        <link rel="icon" type="image/png" sizes="16x16" href="/media/saturntext/logos/favicon-16x16.png">  <!-- Global site tag (gtag.js) - Google Analytics -->

6. Make sure you have also added the correct Pixels, ofcourse be added to the header file
    1. Google Search Console Pixel
    2. Google Analytics Pixel

7. Make sure we have the proper H1-H4 Tag Headers
    1. There should be 1x H1 Tag
    2. There should be at least 2x H2 Tags
    3. H3 tags
    4. H4 tags


8. Make sure to always use raw Javascript, do not use jquery or vuejs or react
    1. You should have only 1 .js file and ofcourse this should have a mininified version


9. After you are finished, Make sure you run a lighthouse audit for both Mobile & Desktop
    1. Make sure you take care of any issues that you can take care of
    2. Whatever you can't take care of, make sure you screenshot it and the team knows about it
