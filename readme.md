# CSS share buttons

![CSS share buttons example](http://www.philswan.co.uk/share/share-buttons.png)

## Why use these?

* They don’t rely on any JavaScript
* They look just like the official versions
* They’re retina friendly
* Speed
* They line up neatly!


## Usage

Copy the files from the `/images` and either `/sass` or `/css` directories to your project, follow the basic HTML structure below, and you’re off.

```
<div class="swinder-social">
    <a href="" class="swinder-social__item swinder-social__item--email"><span></span>Email this</a>
    <a href="" class="swinder-social__item swinder-social__item--facebook"><span></span>Share</a>
    <a href="" class="swinder-social__item swinder-social__item--twitter"><span></span>Tweet</a>
    <a href="" class="swinder-social__item swinder-social__item--google"><span></span><span class="swinder-social__hide">Google +1</span></a>
</div>
```

You can use whatever HTML elements you want, just make sure you follow the same class structure as above. You may also need to edit the `background-image` property values if you use a different directory structure than us.

(But you’re a good developer, so you already know this stuff.)
