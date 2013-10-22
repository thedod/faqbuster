faqbuster
=========

Add annotations as iframe tooltips.

To run a [http://is.gd/shtikipedia](http://is.gd/shtikipedia) clone on localhost:

1. Clone [https://github.com/thedod/faqbuster](https://github.com/thedod/faqbuster) and `cd` there.
1. Drag this bookmarklet to the toolbar:
<a href="javascript:{var style=document.createElement('link');style.rel='stylesheet';style.type='text/css';style.href='https://publishedmodfiles.s3.amazonaws.com/1099/usermod-45.css';document.getElementsByTagName('head')[0].appendChild(style);var js=document.createElement('script');js.setAttribute('type','text/javascript');js.setAttribute('src','http://thedod.github.io/reply2smartid/truthmap.js');document.getElementsByTagName('head')[0].appendChild(js);js=document.createElement('script');js.setAttribute('type','text/javascript');js.setAttribute('src','http://localhost:8000/faqbuster.js');document.getElementsByTagName('head')[0].appendChild(js);void(0);}">fqb</a>
   (Note that it loads the the external [js](http://thedod.github.io/reply2smartid/truthmap.js) and
   [css](https://publishedmodfiles.s3.amazonaws.com/1099/usermod-45.css";document.getElementsByTagName('head) files).
1. Run `python -m SimpleHTTPServer;SimpleHTTPServer` (will serve current folder on port 8080)
1. Go to [the original gov page](http://smartid.gov.il/GeneralInformation/Pages/FAQ.aspx) and click on the bookmarklet.

This repository is for people who want to contribute CSS/JS to the *site independent* part of the project.

To contribute *content* to [shtikipedia](http://is.gd/shtikipedia), please go [here](http://thedod.github.io/reply2smartid).
