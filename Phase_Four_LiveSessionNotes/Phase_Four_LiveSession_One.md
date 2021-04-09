# LiveClass Lecture-One: Customize Your Application Using Bootstrap 

## Prerequsite:

Reference: 
1. [_Go through self-learning_ ](https://www.simplilearn.com/)
2. W3 Schools
3. MDN 

```
Time Frame: [05:5:07]
```

### _FSD Phase 4_:
```
Sec-1: A Front-End Web Developer MasterClass Using HTML, CSS, 
and JavaScript

Sec-2: Build Real World Websites from Scratch Using HTML5 and 
CSS3
```
**This course is divided into two parts:** 
```
 Website Development: 

1. [Static Website] Responsive : HTML, CSS and JavaScript | Bootstrap

2. [Dynamic Website] Responsive : Angular 2+ , SPA (Single Page Web Application)

```
Tools Required: 
```
```
### _Notes_:
-> Static units: 
* Pixel(px)
* inch
* cm

-> Relative Units -> 
   * percentage(%) eg. 50% {Majorly Used}
   * em
   * rem

-> _flow_ 

-> _breakpoints_ : When the screen size changes , the presence of breakpoints allows the content to adapt to the screen size. 

# __Bootstrap__

## _Bootstrap Components_
* Labels 
* Panels
* Jumbotron
* Page Header
* Navbar
* Thumbnails
* Alerts
* List group
* Page Header
* Wells
* Badges
* Dropdowns
* Button groups
* Glyphicons
* Button Drops
* Breadcrumbs
* Input groups
* Navs
* Pagination
* Media Object 

----
## Creating First Page With Bootstrap: Step-1
---
### __Integrate__ __Bootstrap In Three Ways:__

```
1. CDN URL/CDN Link -> remote bootstrap link 

2. Downloading Bootstrap -> local website / webapplication 

3. npm 
-> node.js package manager
-> download with npm 
-> keep with project repository  
```
It's better to use the approach of Downloading Bootstrap.  

**Links**:

1. [Click Here: GetBootstrap](https://getbootstrap.com/) 


# Type-1: Integration Of Bootstrap Using CDN URL 

1. Visit this [link](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
   
2. Copy and past the following stylesheet link inside <head> </head> tag: 
   ```
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">
   ```
   
3. Then copy and past the following javascript plugin into the end of the <body> </body> tag:
   ```
   <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
   
   
   
   <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-Piv4xVNRyMGpqkS2by6br4gNJ7DXjqk09RmUpJ8jgGtD7zP9yug3goQfGII0yAns" crossorigin="anonymous"></script>
   ```

# Type-2: Integration of Bootstrap Using Downloading Files

1. Visit this [link](https://getbootstrap.com/docs/4.6/getting-started/download/) . 

2. **Choose: v4.6** of bootstrap 
   
3. Download : Compiled CSS and JS sec button. 

## Three Important Files Of Bootstrap We Use from downloaded Version: 
```

1) bootstrap.css (or) bootstrap.min.css


2) jquery.js : You do download it separately and provide the link before bootstrp.js script link. 

3) bootstrap.js (or) bootstrap.min.js


```

Keep those particular files, delete others from that. And use it while do responsive web designing.

```
Remember: In this approach if there is no network still you can work. i.e You can work in offline too.And hosting bootstrap locally.  So this is a better approach . 

Do check by :  

1. Opening the webpage -> Right Click -> Inspect -> click the Network Tab and do check  
```

## How to download jquery.js : 
```
1. Copy the jquery.js url from bootstrap cdn link
2. Copy and paste it on the web browser and save this minified version on your working js folder.
that's it. 
3. Now provide the jquery.js link before the bootstrap.js script link inside <body> tag.
```

* Add viewport <meta> tag : For proper touch, zooming and rendering.
  

## Responsive with Bootstrap:

1. Grid system
2. CSS3 media queries


### __TIPS For Visual Studio :__


1. __TO generate tag with class name__: div.className eg. div.container and hit enter tab

2. __To generate tag with id__: div#idName eg: div#unique-param and hit enter tab. 


[Alert Message: Different colours ](https://getbootstrap.com/docs/4.6/components/alerts/)

__Remember:__ 

* Always perform overriding .css file instead of directly change it. 
  
* While designing a website we have following sec:
  
   -> Alert Message 

   -> Navbar with Toggle button

   -> Jumbotron 

   -> Card 

__HomeWork__: Try from your sides

   -> Pagination 

   -> Popovers 

   -> Progress

   -> Scrollspy

   -> Spinners

   -> Toasts

   -> Tooltips