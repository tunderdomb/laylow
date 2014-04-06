ASSETS
======

## fonts

http://www.fontsquirrel.com/tools/webfont-generator
http://www.fontspring.com/blog/the-new-bulletproof-font-face-syntax
http://www.awwwards.com/best-20-webfonts-from-google-web-fonts-and-font-face-embedding.html

CSS
===

    In object-oriented programming, the single responsibility principle states that
    every class should have a single responsibility, and that responsibility should be
    entirely encapsulated by the class. All its services should be narrowly aligned with that responsibility.

https://github.com/stubbornella/oocss/wiki

patch.css
http://csswizardry.com/2013/04/shame-css/

## core

  - attr
    [hidden]
  - html5
    http://html5please.com/
  - pseudo
  - aria
    http://www.w3.org/WAI/PF/aria-practices/
    http://www.w3.org/WAI/PF/aria/roles#abstract_roles
    http://www.w3.org/WAI/PF/aria/states_and_properties#aria-selected
  - util
  - global
    + config
      force-pointer-on-clickables: yes|no
      force-pointer-on-fields: yes|no
      disable-mobile-webkit-highlights: yes|no
      legacy-support: yes|no;
      sensible defaults
      default-roundness: 5px
      default-box-shadow: 0 0 5px black
      box-sizing: border-box
    + media
      phone + landscape | portrait
      tablet + landscape | portrait
      desktop + small | normal | large
      http://stephen.io/mediaqueries
      http://www.texaswebdevelopers.com/blog/template_permalink.asp?id=145
      http://www.andreasnorman.com/css-media-queries-for-mobile-devices/
      http://en.wikipedia.org/wiki/List_of_displays_by_pixel_density
      http://mobile.smashingmagazine.com/2013/03/21/responsive-web-design-with-physical-units/
      http://harrywolff.com/media-queries-viewports-and-responsive-layouts/
    + color
      primary | complement | error | warning | info | success
      selection | em | strong | highlight
      link:hover:focus:visited:active | clickable:hover:focus:visited:active
    + text
      body | link |
    + fun
      layout | text | animation | transition | transform | background+gradient | display | image | border | shapes
  - state/behaviour classes
    .highlight
    .tiny .small .big .large .giant
    light .lighter/.brighter .bright
    .dark .darker/.stronger .strong
    .transparent/.invisible
    .collapsed
    .inline + .middle .top .bottom .left .right
    .block
    .float + .left .right

## reset

  - elements

# grids

http://960.gs/
http://www.responsivegridsystem.com/
http://yui.github.io/gridbuilder/
http://purecss.io/grids/

HTML
====

http://simon.html5.org/html-elements


## header

http://developer.apple.com/library/safari/#documentation/appleapplications/reference/safarihtmlref/Articles/MetaTags.html
http://www.hongkiat.com/blog/responsive-for-mobile-screens/

NOFOLLOW

### meta


### mobile

<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" />
body {
    -webkit-text-size-adjust: none;
}
<!-- 57 x 57 Android and iPhone 3 icon -->
<link rel="apple-touch-icon" media="screen and (resolution: 163dpi)" href="icon57x57.png" />
<!-- 114 x 114 iPhone 4 icon -->
<link rel="apple-touch-icon" media="screen and (resolution: 326dpi)" href="icon57.png" />
<!-- 57 x 57 Nokia icon -->
<link rel="shortcut icon" href="icon57x57.png" />

## images

http://css-tricks.com/which-responsive-images-solution-should-you-use/
https://docs.google.com/spreadsheet/ccc?key=0Al0lI17fOl9DdDgxTFVoRzFpV3VCdHk2NTBmdVI2OXc#gid=0
http://coding.smashingmagazine.com/2013/06/02/clown-car-technique-solving-for-adaptive-images-in-responsive-web-design/

## components

  - editable
    .field, input[...], textarea + .seamless
  - clickable
    .btn, input[...], button
  - table
  - header
  - search
  - sidebar
  - footer

### menu

  +------+------+------+------+------+
  |      |      |      |      |      |
  +------+------+------+------+------+
  - nested
  - jumbotron
  - context
  - nav + vertical/horizontal
  - controlgroup
  - breadcrumbs

### cards

  product
  polaroid
  avatar
  thumbnail

  +---------+
  |         |
  |         |
  |         |
  +---------+
  | ~~~~~~~ |
  +---------+

  +---------+
  | ~~~~~~~ |
  +---------+
  |         |
  |         |
  |         |
  +---------+

### flags

http://csswizardry.com/2013/05/the-flag-object/

+---------+ ~~~~~~~~~~ ~~~~~
|         | ~~~~~ ~~~~~ ~~~~
|         | ~~~~~~~~~ ~~~~~~
|         |
+---------+
+---------+
|         | ~~~~~ ~~~~~ ~~~~
|         | ~~~~~~~~~ ~~~~~~
|         | ~~~~~~~~~ ~~~~~~
+---------+
+---------+
|         |
|         | ~~~~~~~~~ ~~~~~~
|         | ~~~~~~~~~ ~~~~~~
+---------+ ~~~~~ ~~~~~ ~~~~
+---------+ ~~~~~~~~~~ ~~~~~ +---------+
|         | ~~~~~ ~~~~~ ~~~~ |         |
|         | ~~~~~~~~~ ~~~~~~ |         |
|         |                  |         |
+---------+                  +---------+
~~~~~~~~~~ ~~~~~ +---------+ ~~~~~~~~~~ ~~~~~
~~~~~ ~~~~~ ~~~~ |         | ~~~~~ ~~~~~ ~~~~
~~~~~~~~~ ~~~~~~ |         | ~~~~~~~~~ ~~~~~~
                 |         |
                 +---------+

  left-flag, right-flag
    middle-flag, bottom-flag
  figure


.media-left{}
.media-right{}
.media-top{}
.media-bottom{}

    /* ====== media ====== */
    .media {margin:10px;}
    .media, .bd {overflow:hidden; _overflow:visible; zoom:1;}
    .media .img {float:left; margin-right: 10px;}
    .media .img img{display:block;}
    .media .imgExt{float:right; margin-left: 10px;}

## ui

http://groundwork.sidereel.com/?url=ui-elements

  - accordion
  - drawer
  - slideshow
  - progress bar
  - range + single | double
  - meter
  - select + searchable | editable
  - notification
    content | ok | close | custom
  - tabset
    tablist | tab | close | new
    pool | tabpanel
  - dialog
    header | title | close |
    content
    footer | ok | cancel | custom
  - popup
    title | content | ok | cancel
  - scrollpane
    content | scrollbar | handler
  - sortable
  - draggable
  - datalist / autocomplete
  - callout box
  - tooltip


## form

  - stacked
  - aligned
  - grouped
  - inputs
    + checkbox
    + radio
    + progress
      http://www.useragentman.com/blog/2012/01/03/cross-browser-html5-progress-bars-in-depth/
    + file
    + select
         <select>
            <option value="#" disabled>...</option>
            <option></option>
          </select>
  - fieldset
  - legend
  - field-title


# layouts

  \ Three Boxes
  \ Five Boxes
  \ Advanced Grid
  \ Power Grid
  \ Fixed Sidebar
  \ Headline & Gallery
  \ 3D Screenshots
  \ Featured Graphic
  \ Featured Photo
  \ Full Screen Photo

  !http://designshack.net/articles/layouts/10-rock-solid-website-layout-examples/
  http://webdesignledger.com/inspiration/21-clean-web-design-layouts
  http://webdesignledger.com/inspiration/48-examples-of-excellent-layout-in-web-design
  http://www.awwwards.com/50-examples-of-responsive-web-design.html
  http://vandelaydesign.com/blog/design/unique-website-layouts/
  http://www.hongkiat.com/blog/60-high-quality-free-web-templates-and-layouts/
  http://www.thebestdesigns.com/
  http://speckyboy.com/2012/02/29/40-examples-of-brilliant-responsive-website-layouts/
  !http://www.hongkiat.com/blog/responsive-for-mobile-screens/
  !http://www.hongkiat.com/blog/web-design-trend-2013/
  !http://www.hongkiat.com/blog/tag/ecommerce/
  !http://sixrevisions.com/design-showcase-inspiration/responsive-webdesign-examples/
  http://www.smashingmagazine.com/2008/09/03/40-creative-design-layouts-getting-out-of-the-box/
  !http://webdesignledger.com/
  !http://99designs.com/designer-blog/2013/02/21/web-design-trends-for-2013/
  http://designm.ag/inspiration/34-flat-layouts-design-inspiration/
  !http://ivomynttinen.com/work/

  http://www.creativebeacon.com/wee-responsive-html5-theme/

JavaScript
==========

## dom

  .get
    .byId | byAttr | byClass | byTag | byItemId | byData | byRole

## ajax

## resource loader

## storage

  local
  session
  cookie
  localFileSystem
  postMessage

## roles

  dismissable (hit x to close)

## tempaltes

## canvas

## form

Tools
=====
