# PO Box
## This is where we store our common assets, i.e. stylesheets, javascript, and images.

### What this is:
We use this to serve static assets to our applications. The assets themselves are generated using our [styleguide](https://github.com/postcode/styleguide). Once changes are made to the styleguide you can push the generated css into this repository. All the applications that link to postcode_main.css will pull in the new styles. Easy!

### How to use:
In your application point your css, js, images to the hosted version of the files. This is setup as a Heroku app:

[http://pure-garden-9104.herokuapp.com/](http://pure-garden-9104.herokuapp.com/)

So to use the main css file in your app do this:

```html
<link href='http://pure-garden-9104.herokuapp.com/css/postcode_main.css' rel='stylesheet' type='text/css'>
```

Or the PostCode image:

```
<img src="http://pure-garden-9104.herokuapp.com/images/postcode_logo_blue.png">
```