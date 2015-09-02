# CSS share buttons

![CSS share buttons example](http://www.philswan.co.uk/share/share-buttons.gif)

## Why use these?

* They don’t rely on any JavaScript
* They look like the official versions, but line up!
* They’re retina friendly
* Speed


## Usage

Copy the files from the `/images` and either `/sass` or `/css` directories to your project, follow the basic HTML structure below, and you’re off.

```
<div class="swinder-social">
    <a href="" class="swinder-social__item swinder-social__item--email"><span></span>Email this</a>
    <a href="" class="swinder-social__item swinder-social__item--facebook"><span></span>Share</a>
    <a href="" class="swinder-social__item swinder-social__item--twitter"><span></span>Tweet</a>
    <a href="" class="swinder-social__item swinder-social__item--google"><span></span><span class="swinder-social__hide">Google +1</span></a>
    <a href="" class="swinder-social__item swinder-social__item--linkedin"><span></span>Share</a>
</div>
```

You can use whatever HTML elements you want, just make sure you follow the same class structure as above. You may also need to edit the `background-image` property values if you use a different directory structure than us.

(But you’re a good developer, so you already know this stuff.)

## Contribution formatting and compiling

Read these quick rules before contributing to `sass/swinder-social.scss`:

- 1 single space between selector and opening declaration block curly bracket
- Use multi-line CSS for both selectors and declaration blocks
- Alphabetise declarations within your declaration blocks
- @includes go at the top of a declaration block (in case we need to override them)
- No space between declaration property and value
- Always use a trailing semicolon on the last declaration within a declaration block.
- Any SASS functions (percentage, em etc) should have spaces between math operators. For example percentage(20 / 940) rather than percentage(20/940) for legability

Lastly, when committing compiled `CSS` changes, please compile with the following Terminal command: `sass --watch sass:css --style expanded --sourcemap=none`
