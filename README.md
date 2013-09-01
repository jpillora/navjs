
# *In progress*

---

# Nav.js

A vanilla JavaScript library to automate the generation of complex navigation menus

## The Problem

For pages with large portions of content, like: long blog posts, technical documentation, 
online books, etc. we'll most like want a comprehensive table of contents (or a *set* of navigation menus)
to assist discovery. Although keeping this long list of links in sync with the actual content is
laborious task, so, JavaScript to the rescue.

## The Solution

**Nav.js** - We'll run:

``` js
Nav("div#nav");
```

On our page, with content:

``` html
<div id="nav"></div>
<div data-nav="Home">...</div>
<div data-nav="Projects">...</div>
<div data-nav="Contact">...</div>
```

Which will provide `div#nav` with the following `ul`:
``` html
<div id="nav">
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</div>
```

Essentially performing the **only** the "Add Markup" portion of
[Responsive Nav's Instructions](http://responsive-nav.com/#instructions).
Since this library has no opinions on styling, it may be used with any CSS framework.

## Features

* Automatic generation of markup
* Unlimited submenu depth
* Automatically scroll to section based on nav clicks
* Automatically scroll to navigation items based on window scroll position
* Hide and show submenus based on view-port
* Animate scrolling and hide/shows
* Bookmarkable hash links

## Download

*...*

## Examples

*...*

## API

**`Nav(options)`**

`options` may a selector string (`container`)

`options` may be be an object with:

* `container` - The selector used to find the navigation menus container (**required**)

### Todo

*...*

#### MIT License

Copyright © 2013 Jaime Pillora &lt;dev@jpillora.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



