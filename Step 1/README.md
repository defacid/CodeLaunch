# Step 1: Introduction

First we establish the base of the site - we include a DOCTYPE to let browsers and web crawlers know what kind of code is included and use the HTML wrapper to signify where our HTML will actually go.

```html
<!DOCTYPE html>
<html>
</html>
```

Inside the HTML tags, we'll need a `<head>` that will send all of the meta information and include any external files that are necessary to website design or function (like CSS or Javascript) and we'll need a `<body>` that will show all of the content that will be displayed.

```html
<!DOCTYPE html>
<html>
  <head></head>
  <body></body>
</html>
```

An example of something that goes in the `<head>` would be a title that allows you to set the text that displays at the top of a tab or window. Inside the body, we will place the content we want to display - as a general rule, it's good to block off content into sections like `<div>` or `<span>` to keep content organized, but the browser will still read the content with or without organizational sections.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Portfolio</title>
  </head>
  <body>
    <div>Hello, world!</div>
  </body>
</html>
```

Lastly, it's not necessary for a website to function, but it's good practice to include either a language attribute in the HTML tag or a meta charset attribute in the `<head>` to make it easier for browsers, and users, to know what language the website is in.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Portfolio</title>
  </head>
  <body>
    <div>Hello, world!</div>
  </body>
</html>
```
