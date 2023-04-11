# Emoji's picker
Simple &amp; light emojis picker. It supports over 1400 emojis.

<img src="https://github.com//alirq/emoji-picker/blob/main/screenshot.png?raw=true" alt="Emoji's picker twemoji js css html github">

## Demo

https://codepen.io/alirq/pen/XWxJqPO

### How to use

Add ep.min.js file in your page at the bottom of the body

Now simply pass your targeted textarea's to the plugin function as bellow example

`new epicker('#textarea');`

`<script src="ep.min.js"></script>`

Place the bellow HTML tag to where you wish the picker to show

`<div id="ep__picker"></div>`

Add ep.min.css file in your page's head

`<link rel="stylesheet" href="ep.min.css">`

## Parameters

If you wish to prevent certain emojis from being pasted by user

`new epicker('#textarea', false, false, '😀,🙃');`

Or as an array

`var array = ["😀","🙃"];`

`new epicker('#textarea', false, false, array');`

To avoid useing external css file, pass true to the function to enable the inline css tag.

`new epicker('#textarea', true, false, ['']);`

The third parameter (false), If the targeted html element Is not TEXTAREA or INPUT and you wish to change the whole element's content instead of append it, pass another true to achieve that.

`new epicker('#textarea', true, true, '😀,🙃');`

