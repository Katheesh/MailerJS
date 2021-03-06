# Mailer JS
### This package has a powerful laravel back-end application for posting mail service. 
#### [We will never send you unsolicited 'junk' email, or share your data with anyone else who might.](https://gitleaf.com/privacy-policy)
#### Package developed by [S.Katheeskumar](https://katheesh.github.io) 
<img src="https://gitleaf.com/img/quote.png"/>
<hr/>

## Installation

#### Install using npm
```bash
# install it via npm
npm install @katheesh/mailer-js --save

OR

npm i @katheesh/mailer-js
```

<hr>

#### [GitLeaf](https://gitleaf.com/) Officially uses `mailer-js` for their mailing module.

## Usage
```bash
    # to = Reciever Email Address
    # from = Sender Email Address
    # subject = Email Main Subject
    # title = This title appear on top of body in h2 
    # body = add this parameter like plain text or html or markdown
```

#### javascript

```javascript

var Mailer = require("mailer-js");

var Data = 
{
    "to": "your-email@sample.com",
    "from":"no-replay@domain.com",
    "subject": "Sample Mail from mailer-js",
    "title": "Sample Mail from mailer-js",
    "body"  : "Hello there, I'm Katheeskumar. 
                I love coding and proud to present this open source application"
}
//  Html / Plaintext mailing
console.log(Mailer.prepare(Data)) // i'ts return json format

//  Markdown mailing
console.log(Mailer.prepareMarkdown(Data)) // i'ts return json format

```



## Browser Support

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |
--- | --- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | 11 ✔ |

##### [Support & Become a Patron!](https://www.patreon.com/bePatron?u=32135007) 
<a href="https://www.patreon.com/bePatron?u=32135007" data-patreon-widget-type="become-patron-button"><img src="https://i.ya-webdesign.com/images/patreon-link-button-png-2.png"/></a>
<hr>

## License

This project is licensed under MIT of
[@Katheesh](https://katheesh.js.org/).
