[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/koada-os/invisible-recaptcha)

# <invisible-recaptcha>

A Polymer Invisible Recaptcha web-component for 🤖 detection (Polymer 1.x)

`<invisible-recaptcha>` is an web-component implementation of the Invisible Recaptcha by Google.

### How to detect 🤖 :

1. You need to get an API Key here: http://www.google.com/recaptcha/admin (select invisible Recaptcha)
2. Place the element where you want
3. When you want to make the verification, just call the verify function.
4. Wait the end of the verification. `verification-finished` will fire.
5. Verify the token with your backend. see https://developers.google.com/recaptcha/docs/verify for more informations.

### How to use inside shadow-dom :

1. Set the `shadow-dom` attribute.
2. When you open the form call `render()`
