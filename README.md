# Portfolio website

This is a lightweight, pure HTML & CSS, portfolio website template which is free to be used and adopted for anyone.

> Small note: I've added a `script.js` to illustrate how to potentially add JavaScript, if you have no need for JavaScript, you can remove the `script.js` as well as remove the `<script>` tags in the HTML documents.

### Core focus

- **Semantic markup** (`nav`, `section`, `figure`, etc.), improving structural readability
- **CSS variables**, making it easy to configure things once and reuse across stylesheet
- **CSS Grid**, flexible multi-column layouts
- **Media queries**, responsive design for any device

### Table of contents

- [Portfolio website](#portfolio-website)
    - [Core focus](#core-focus)
    - [Table of contents](#table-of-contents)
    - [Map structure](#map-structure)
  - [Web typography](#web-typography)
  - [Preparing media for online use](#preparing-media-for-online-use)
    - [Images](#images)
    - [Videos](#videos)
  - [How to take it further](#how-to-take-it-further)
  - [Getting your website online](#getting-your-website-online)
    - [Domain](#domain)
    - [Hosting](#hosting)
    - [Hosting companies \& domain providers](#hosting-companies--domain-providers)
  - [Portfolio inspiration](#portfolio-inspiration)
  - [Website tutorials](#website-tutorials)

### Map structure

```
assets/
├── fonts/             (contains all web-friendly font files, i.e. woff or woff2)
|   └── authentic-sans-90.woff
├── scripts/           (contains all JavaScript scripts)
|   └── script.js
└── stylesheets/       (contains all CSS stylesheets)
|   └── style.css
└── favicon.png        (the icon shown in the browser's tab)
work/                  (contains all projects)
├── project-title-a/   (folder renamed to the project's title in lowercase and with all spaces replaced as dashes)
|   ├── media/         (the project's media, i.e. images, videos, and audio)
|   └── index.html     (the project's HTML page)
index.html             (the homepage's HTML page)
```

## Web typography

Web fonts are specific files (.woff or .woff2) which you can use in CSS to use on your website. There are many free-to-use fonts for on the web and also a tool to convert other font files (.ttf, otf) to web font files with Font Squirrel but keep in mind that font licenses are specific to the usage. So if you buy a print- or desktop-license for a font you're not allowed to use it online unless you buy the web-license as well.

**Web font resources**

- Open Foundry **—>** [open-foundry.com](https://open-foundry.com/)
- Badass Libre fonts by womxn **—>** [design-research.be](https://www.design-research.be/by-womxn/)
- Adobe Typekit **—>** [fonts.adobe.com](https://fonts.adobe.com/)
- Google Fonts **—>** [fonts.google.com](https://fonts.google.com/)
- Font Squirrel **—>** [fontsquirrel.com](https://www.fontsquirrel.com/)

## Preparing media for online use

You will be using lots of media and files on your website from images to videos and fonts. It's important to be optimal in terms of sizes and resolutions to get your website to respond quickly and work properly. Also when looking at prices above it will cost you literally money if you are not optimal with your file sizes. 

Below are some general rules and best practices regarding using media.

### Images

Image files can make your website super slow, I often see wrong settings used so below are some general rules you need to follow to keep your website light, fast and proper.

1. Size: keep your image sizes below **200 kb** (yes that is kilo bytes!)
2. Resolution: don't use images that exceed **1920px width or height**
3. DPI: use maximal **150 dpi**
4. JPG or PNG: for photos use JPG but for vector images use PNG
5. GIF: don't use GIF files

### Videos

It's highly recommended to upload your videos to a service such as YouTube or Vimeo because their servers are much faster and they provide good embedding options.

1. Codec: use **H.264** this will reduce file size and keep quality
2. File format: use **.mp4**
3. MOV: don't use MOV files

**YouTube embedding**

To embed a YouTube video take these steps:

1. Upload video on YouTube
2. Go to video page when it's uploaded
3. Click on the **share** button below video
4. Click on the **embed** button in popup window
5. Copy code
6. Paste in your html document where you want the embedded video

**Vimeo embedding**

To embed a Vimeo video take these steps:

1. Upload video on Vimeo
2. Go to video settings page when it's uploaded
3. Click on **embed** tab on the left navigation panel
4. Click on dark blue **embed code** button (this copies code for you to clipboard)
5. Paste in your html document where you want the embedded video

**Autoplay**

As of 2019 browsers block autoplaying videos, the rule is now that if a user visits a website they need to interact first in order for videos to play. This is to protect users. I believe **Vimeo Pro** still has a way for autoplay to work but best and easiest practice is to simply have videos that play upon click.

## How to take it further

- [How to - Portfolio Gallery with Filtering](https://www.w3schools.com/howto/howto_js_portfolio_filter.asp)
- [How to - Mobile Navigation Menu](https://www.w3schools.com/howto/howto_js_mobile_navbar.asp)
- [How to - Image Gallery](https://www.w3schools.com/howto/howto_js_tab_img_gallery.asp)
- [How to - Fullscreen Video](https://www.w3schools.com/howto/howto_css_fullscreen_video.asp)
- [How to - Popup/Modal](https://www.w3schools.com/howto/howto_css_modals.asp)
- [How to - Scroll Progress Indicator](https://www.w3schools.com/howto/howto_js_scroll_indicator.asp)
- [How to - Smooth Scroll](https://www.w3schools.com/howto/howto_css_smooth_scroll.asp)
- [How to - Custom Scrollbar](https://www.w3schools.com/howto/howto_css_custom_scrollbar.asp)
- [How to - Draggable HTML Elements](https://www.w3schools.com/howto/howto_js_draggable.asp)

## Getting your website online

### Domain

A domain name is a unique name specific for your website, it's what you type in your address bar. Its price varies depending on the name and the extension. Some extensions are more expensive than others.

You can register domains separately but easiest is to get it together with hosting so that your domain and web server are automatically linked and setup.

Domains differ in price based on how popular/general a name is (i.e. 'bestdeals' vs. 'louisbraddock') and the extension (i.e. '.com' is cheaper than '.io').

**Do you need a domain?**

Not necessarily.

If you don't mind a URL which isn't something like "yourname.lol" or "myname.xyz" or "studioname.com" then you can use things like GitHub Pages or Netlify to host your website and those come with their own default url, i.e. https://username.github.io or https://something.netlify.app.

Personally, I think having a unique domain name is nice but its not for free so you decide obviously.

### Hosting

Hosting is a service you buy to get server space allocated. For instance you can get 10GB space and pay a yearly fee. With this you usually get some extra services such as: email and FTP.

Before people can see your website that you put on your server you need a domain, as mentioned before it's easiest to get a domain and hosting together.

**How much space do you need?**

**5** **gigabytes** is more than enough. As explained in the using media section below you need to really take care of file size and this will reduce the costs needed for hosting.

**Do you need hosting?**

No, actually not.

If you have your own domain name – or if you haven't – hosting is optional, using GitHub Pages or Netlify you can easily host your Github repository for free!

Having your own server is great, its yours and it will always be yours as long as you keep paying but having it is maybe overkill for your portfolio website which won't have thát much content. Seeing that hosting plans start at 5 gigabytes that's a lot of space which you won't use.

### Hosting companies & domain providers

Make sure to compare prices between hosting & domain providers, it differs quite a bit! These companies offer both hosting and registering domains.

- [Vimexx](https://www.vimexx.com)
- [Namecheap](https://www.namecheap.com)
- [Webreus](https://www.webreus.nl)
- [one.com](https://www.one.com)
- [Hostgator](https://www.hostgator.com)
- [Antagonist](https://www.antagonist.nl)
- [Neostrada](https://www.neostrada.com)
- [Godaddy](https://www.godaddy.com)

## Portfolio inspiration

- [Studio Feixen](https://www.studiofeixen.ch)
- [United Visual Artists](https://www.uva.co.uk)
- [Afrika](https://www.afrika.to)
- [Node](https://node.international)
- [Michel Egger](https://www.michelegger.ch)
- [Formafantasma](https://formafantasma.com)
- [Parabol Studio](https://parabolstudio.no)
- [Sara Kaaman](https://www.sarakaaman.com)
- [Elina Birkehag](https://elinabirkehag.com)
- [Studio Darius Ou](https://dariusou.work)
- [Medusa](https://medusaoffspace.com)
- [Werker Collective](https://www.werkercollective.net)
- [Zeno Beikircher](https://zenobei.com)
- [Büro Vivien Hoffmann](http://www.vivienhoffmann.com)
- [Studio Remco van Bladel](https://remcovanbladel.nl)

## Website tutorials

- [Create a Free Website](https://www.w3schools.com/spaces/index.html)
- [Build a Website with HTML, CSS, and GitHub Pages](https://www.codecademy.com/learn/paths/learn-how-to-build-websites)
- [How to Make a Website with NameCheap](https://www.codecademy.com/learn/make-a-website)
- [How to Deploy a Website](https://www.codecademy.com/learn/deploy-a-website)