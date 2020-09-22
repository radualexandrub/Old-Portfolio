# radualexandrub.github.io
[My first Portfolio!](https://radualexandrub.github.io/)

## About:
At first I thought it's easy to make a personal portfolio (just grab a template and edit with your info), but it is more than that. Even if this is a static website, I still had to edit some of the CSS and JS files in order to make this site as responsive and fluent as possible (especially on mobile devices). Sometimes it's not that easy to just copy-paste elements from the Internet - it's also important to find the best ways to integrate those elements into the project.

The best way to learn something is by doing it yourself! However, you can use this whole website as your portfolio, if you want (without changing anything but your name and projects), but I don't recommend doing this for your learning experience! :D

I also provided a full step-by-step guide bellow **(from my experience)** to make this web portfolio visible/searchable on Google.

## Links I've used:
- [Start Bootstrap - Bootstrap themes, Templates and more](https://startbootstrap.com/)
- [Font Awesome icons (free version)](https://fontawesome.com/icons?m=free)
- [Devicon - Icons for programming languages & development tools](https://devicons.github.io/devicon)
- [w3schools - Images with transparent text](https://www.w3schools.com/howto/howto_css_image_transparent.asp)
- [JQuery LightSlider - Responsive Content slider with carousel thumbnails navigation](https://sachinchoolur.github.io/lightslider/index.html)
- [MockUPhone - Screenshots device mockups generator](https://mockuphone.com/)
- [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/) - Best Free Stock Photos with No Licenses Required

## **My steps / My journey** for improving Google SEO (Search Engine Optimization):
- Add these *meta tags* in your `index.html`:
    ```HTML
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
    <meta name="description" content="YOUR NAME/DESCRIPTION | PORTFOLIO/BLOG/etc" /> <!-- It appears when you send the link through Fb/Wapp/etc -->
    <meta name="author" content="YOUR NAME" />
    <meta property="og:title" content="YOUR NAME/DESCRIPTION | PORTFOLIO/BLOG/etc">
    <meta property='og:image' content='//media.example.com/ 1234567.jpg'/>
    <meta property='og:description' content='Description that will show in the preview'/>
    <meta property='og:url' content='//www.example.com/URL of the article'/>
    ```
- Use [Optimizilla - Online image optimizer to shrink images to the minimum possible size while keeping the quality](https://imagecompressor.com/)
- Check Site performance with [PageSpeed Insights from Google](https://developers.google.com/speed/pagespeed/insights/)
- Generate [sitemap.xml](https://www.xml-sitemaps.com/) and [robots.txt](https://en.ryte.com/free-tools/robots-txt-generator/)
    - In robots.txt, add `Sitemap: https://[your-website-name].github.io/sitemap.xml`
- Add [Google Tag Manager](https://marketingplatform.google.com/about/tag-manager/) (+ Paste snippets to index.html)
- Add website to [Google Analytics](https://analytics.google.com/analytics/web) (+ Paste snippet to index.html)
- Add website to [Google Search Console](https://search.google.com/search-console/about) using "URL prefix" method
    - In Google Search Console app, add "[your-website-name].github.io/sitemap.xml" in `sitemap` tab.
    - *Wait 3-4 days* until "Overview", "Performance" and "Coverage" tabs are fully functional in your Google Search Console
    - (In "Coverage" tab) If your main page appears to be "Excluded", click on it on an then in *"Coverage > Discovered – currently not indexed > Examples"* click on "Inspect URL" icon. Here you can also perform a "Live Test" to see if your page is loaded successfully
    - Wait 10 to 30 minutes
    - Now your page should appear on Google Search. You can check it by searching on Google: `site:[your-website-name].github.io`




