Bad ~~Wolf~~ Dog
================

This is a personal fork of [Bad Wolf](https://github.com/sjl/badwolf). A color scheme for Vim, originally pieced together by [Steve Losh](http://stevelosh.com/).

This fork includes special neovim treesitter settings for vimscript, C, and Lua.

Screenshots
-----------

These screenshots may be out of date, but they'll at least give you a taste of
what you're in for.

### Python

![Screenshot](http://i.imgur.com/fQGGC.png)

### HTML (Django Templates)

![Screenshot](http://i.imgur.com/LgLar.png)

### Clojure

![Screenshot](http://i.imgur.com/THHz7.png)

### Markdown

![Screenshot](http://i.imgur.com/J56VS.png)

Configuration
-------------

There are a few settings you can use to tweak how Bad Dog looks.

### g:baddog\_darkgutter

Determines whether the line number, sign column, and fold column are rendered
darker than the normal background, or the same.

    " Make the gutters the same color as the background.
    let g:baddog_lightgutter = 1

### g:baddog\_tabline

Determines how light to render the background of the tab line (the line at the
top of the screen containing the various tabs (only in console mode)).

Can be set to `0`, `1`, `2`, or `3`.

    " Make the tab line darker than the background.
    let g:baddog_tabline = 0

    " Make the tab line the same color as the background.
    let g:baddog_tabline = 1

    " Make the tab line lighter than the background.
    let g:baddog_tabline = 2

    " Make the tab line much lighter than the background.
    let g:baddog_tabline = 3

Default: `1` (same color as the background)

### g:baddog\_html\_link\_underline

Determines whether text inside `a` tags in HTML files will be underlined.

    " Turn off HTML link underlining
    let g:baddog_html_link_underline = 0

Default: `1` (on)

### g:baddog\_css\_props\_highlight

Determines whether CSS properties should be highlighted.

    " Turn on CSS properties highlighting
    let g:baddog_css_props_highlight = 1

Default: `0` (off)
