Additional features:
- Font selection
- Line height slider
- Dark mode switch

Usage:

1. Copy the repository
1. grap the example folder
1. double click on the `index.html`
1. edit your presentation text in the built-in editor (press `Escape` to open it)
1. export your presentation via `save` button (save the `presentation.html` nearby the `index.html`) or copy paste your presentation text right into the `index.html`'s script section

# sentjs
Simple plaintext presentation tool.  Ported from [sent](https://tools.suckless.org/sent/).

## Example:

Create an HTML file containing your presentation slides where each slide is separated by a blank line:
```html
<meta charset="utf-8">
<script src="sent.js">
@http://www.nyan.cat/cats/original.gif
this text will not be displayed, since the @ at the start of the first line
makes this paragraph an image slide.

sentjs

Why?

get your point across fast

simple to use

2 slide types
🖹 Text
🌼 Image

built-in editor
⇒press escape

depends on
♽ HTML5
☢ CSS3
☃ JavaScript

usage:
\ 
<meta charset="utf-8">
<script src="http://unpkg.com/sentjs">
slide 1
\ 
slide 2
\ 
etc
<\/script>

one slide per paragraph

lines starting with # are ignored

image slide == paragraph containing @URL

empty slide == just use a \\ as a paragraph

Use \\<space> for a blank line in a slide

# This is a comment and will not be part of the presentation

# multiple empty lines between paragraphs are also ignored



\@this_line_actually_started_with_a_\\.png
\#This line as well
⇒ Use backslash to kill behaviour of tags

UTF-8 support:
\ 
😀😁😂😃😄😅😆😇😈😉😊😋😌😍😎😏
😐😑😒😓😔😕😖😗😘😙😚😛😜😝😞😟
😠😡😢😣😥😦😧😨😩😪😫😭😮😯😰😱
😲😳😴😵😶😷😸😹😺😻😼😽😾😿🙀☠

Thanks to ⇒
     ▸ Takahashi
     ▸ suckless.org

fini

# must have closing script tag
</script>
```

Then view the file in your browser.  Use arrow keys to navigate.  F11 for fullscreen.  ESC to open editor.

