# Emoji's picker
Simple &amp; light emojis picker. It supports over 1400 emojis.

<img src="https://github.com//alirq/emoji-picker/blob/main/screenshot.png?raw=true" alt="Emoji's picker twemoji js css html github">

**Demo**

https://codepen.io/alirq/pen/XWxJqPO

**How to use**

Add ep.min.js file in your page at the bottom of the body

`<script src="ep.min.js"></script>`

Place the bellow HTML tag to where you wish the picker to show

`<div id="ep__picker"></div>`

Now simply pass your targeted textarea's to the plugin function as bellow example

`new epicker('#textarea');`

If you wish to prevent certain emojis from being pasted by user

`new epicker('#textarea', '😀,🙃');`

Or as an array

`var array = ["😀","🙃"];`
`new epicker('#textarea',array');`

**Style/CSS**

Add ep.min.css file in your page's head

`<link rel="stylesheet" href="ep.min.css">`

If you want to avoid useing this external css file, pass true to the function to enable the inline css tag.

`new epicker('#textarea', '😀,🙃', true);`

**Hints:**
1.You can pass your .class name or #id or even the tag name.
2.The plugin works with text input and textarea tag.
