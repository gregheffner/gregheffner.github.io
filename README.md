# Greg Heffner's GitHub Page

Welcome!

This page is a redirect from `gregheffner.github.io` to `https://greg.heffner.live/blog.html`.

## Redirect Information

If you've landed on this GitHub page, you're likely looking into how I did the redirect to [Greg Heffner's personal website](https://greg.heffner.live/blog.html).


## Details: 


This line specifies the character encoding for the HTML document. utf-8 supports all characters and symbols in Unicode.
```bash
meta charset="utf-8"
```
This line sets the title of the webpage, which is displayed in the browser's title bar or tab.
```bash
<title>Redirecting to https://greg.heffner.live/blog.html</title>:
```
This line is where the redirection actually happens. The http-equiv="refresh" attribute is used to refresh and redirect the page. The content attribute specifies the delay before the refresh (in this case, 0 seconds), and the URL to redirect to.
```bash
<meta http-equiv="refresh" content="0;URL=https://greg.heffner.live/blog.html">:
```
This line is used for SEO (Search Engine Optimization) purposes. It tells search engines that the canonical (the preferred version of a web page) URL is https://greg.heffner.live/blog.html. This helps prevent duplicate content issues.
```bash
<link rel="canonical" href="https://greg.heffner.live/blog.html">:
```
