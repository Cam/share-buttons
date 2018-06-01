# share-buttons [![version](http://img.shields.io/badge/release-v1.0.0-brightgreen.svg?style=flat)](https://github.com/wcoder/share-buttons/archive/master.zip) [![license](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](https://github.com/wcoder/share-buttons/blob/master/LICENSE)

Simple social buttons for your site.

## [Demo](https://wcoder.github.io/share-buttons/)

## Browser support

* Google Chrome
* Mozilla Firefox 3.5+
* Opera 10+
* Safari 3.2+
* IE 8+
* Android
* iOS

## Install

NPM:

```sh
npm i share-buttons
```

include `share-buttons.js` in the end of page:

``` html
<script src="<path>/dist/share-buttons.js"></script>
```

Paste this html on the page:

``` html
<div class="share-btn">
    <a class="btn-vk" data-id="vk">VK</a>
    <a class="btn-facebook" data-id="fb">Facebook</a>
    <a class="btn-twitter" data-id="tw">Twitter</a>
    <a class="btn-telegram" data-id="tg">Telegram</a>
    <a class="btn-mail" data-id="mail">EMail</a>
</div>
```

Added styles:

``` css
.share-btn > a {
    border: 1px solid #ccc;
    padding: 5px;
    font-size: 12px;
    font-family: Verdana, Arial;
}
.share-btn > a:hover {
    cursor: pointer;
}
```

Profit!!

## Customizing

Custom 'url', 'title', 'description':

``` html
<div class="share-btn" data-url="https://..." data-title="..." data-desc="...">
    <a class="btn-vk" data-id="vk">VK</a>
    <a class="btn-facebook" data-id="fb">Facebook</a>
    <a class="btn-twitter" data-id="tw">Twitter</a>
    <a class="btn-telegram" data-id="tg">Telegram</a>
    <a class="btn-mail" data-id="mail">EMail</a>
</div>
```

Styles - full customization.

## Examples

If your using [Font-Awesome](https://github.com/FortAwesome/Font-Awesome):

```html
<div class="share-btn" data-url="https://..." data-title="..." data-desc="...">
    <a class="btn-vk" data-id="vk"><i class="fab fa-vk"></i> VK</a>
    <a class="btn-facebook" data-id="fb"><i class="fab fa-facebook-square"></i> Facebook</a>
    <a class="btn-twitter" data-id="tw"><i class="fab fa-twitter"></i> Twitter</a>
    <a class="btn-telegram" data-id="tg"><i class="fab fa-telegram"></i> Telegram</a>
    <a class="btn-mail" data-id="mail"><i class="fas fa-at"></i> EMail</a>
</div>
```

----

&copy; 2015 - Yauheni Pakala
