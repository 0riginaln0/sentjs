# sentjs

Simple plaintext presentation tool.  Ported from [sent](https://tools.suckless.org/sent/).

## Additional features:

- Font selection
- Line height slider
- Dark mode switch

## Usage:

1. Copy the repository
1. double click on the `index.html`
1. edit your presentation text in the built-in editor (press `Escape` to open it)
1. export your presentation via `save` button (save the `presentation.html` nearby the `index.html`) or copy paste your presentation text right into the `index.html`'s script section
1. done! Give your awesome presentation!

## Example:

Create an HTML file containing your presentation slides where each slide is separated by a blank line:

```html
<meta charset='utf-8'>
<link rel="stylesheet" href="styles.css">
<script src='sent.js'>

sentjs

Why?

get your point across fast

simple to use

depends on:
- HTML5
- CSS3
- JavaScript

usage:
\ 
<meta charset="utf-8">
<link rel="stylesheet" href="styles.css">
<script src="sent.js">
slide 1
\ 
slide 2
\ 
etc
<\/script>

2 slide types
  • Text
  • Image (and GIFs)

built-in editor
=> press escape

> one slide per paragraph*
> lines starting with # are ignored
> image/gif slide: paragraph containing @FILENAME
> empty slide: just use a \\ as a paragraph

# Image from local folder
@PNG_transparency_demonstration_1.png

# GIF from local folder
@cat-space.gif

# Image from URL
@https://cataas.com/cat

# GIF from URL
@https://www.nyan.cat/cats/original.gif

The next slide is empty

# Empty slide is just \
\

*You can have several paragraphs in one slide
\ 
 Use \\<space> for a blank line in a slide

# Use \ to escape \ or # or @
\@this_line_actually_started_with_a_\\.png
\#This line as well
=> Use backslash to kill behaviour of tags

UTF-8 support:
\ 
😀😁😂😃😄😅😆😇😈😉😊😋😌😍😎😏
😠😡😢😣😥😦😧😨😩😪😫😭😮😯😰😱

Thanks to ⇒
     ▸ Takahashi
     ▸ suckless.org
     ▸ Philip Bohun
     ▸ github.com/dfadev
     ▸ vshakitskiy

thanks.
questions?

How to present code snippets?

Well, use either image or text :)

@Fonts.png

\@font-face {
    font-family: 'JetBrains Mono';
    src: url('./fonts/JetBrainsMono-Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}
\ 
\@font-face {
    font-family: 'Iosevka';
    src: url('./fonts/Iosevka-Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}

</script>

```

Then view the file in your browser. Use arrow keys to navigate. F11 for fullscreen. ESC to open editor.
