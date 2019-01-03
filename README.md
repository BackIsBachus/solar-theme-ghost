Solar Theme for Ghost
=====================

A stylish theme for [Ghost](http://ghost.org/) blogs, based on the [Solarized](http://ethanschoonover.com/solarized) color palette.

![Screenshot](http://i.imgur.com/P94J69S.png)

Solar Theme for Ghost
=====================

### A fork from [mattvh/solar-theme-ghost](https://github.com/mattvh/solar-theme-ghost) and some changes from [serenader2014/solar-theme-ghost](https://github.com/serenader2014/solar-theme-ghost)

What's added ?
--------

- Improve stylesheet. Images in the mobile broswer will display well.
- Using `background-image` instead of `<img />` tag. More flexible.
- Fix for Ghost 1.0 Compatibility (for theme version 2.x)
- Fix for Ghost 2.0 Compatibility (for theme version 3.x +)
- Remove blueimp-gallery to only keep basic functionalities (for the version 4.x +)

Features
--------

* **Two color schemes** — One for Solarized Dark and one for Solarized Light. Just swap the reference to the `colors-dark.css` file with `colors-light.css` if you don't like light-on-dark.
* **Responsive Design** — Solarized adapts to fit any screen size.
* **Navigation** — Support for the Navigation menu of the Design pannel

Which version do I need?
--------
- For Ghost 1.x chose the theme version 2.x
- For Ghost 2.x chose the theme version 3.x

Installation
------------

**These installation steps suppose you  are using Ghost > 1.0**

1. Download the lasttes zipped release relevent for your Ghost version

2. Go to the Admin part or your Ghost instance on the Design pannel

3. Click on "Upload theme" and drop the zip on the upload window

4. Either activate it right after the upload is finished or later on the Design pannel

5. (Optional) Setup you Navigation bar in the Design pannel with several pages (Home, About, RSS, etc)


Customization
-------------

Solar supports Ghost's logo and cover image features, and will work perfectly fine with or without them. If you wish to upload a cover image, it will appear above the rest of the page. An uploaded logo replaces the textual blog name. (If you later decide you don't want a logo or cover image, you can remove it by clicking on the appropriate option in Settings and selecting the trash can icon.)


Syntax Higlighting
------------------

Solar uses [Prism.js](http://prismjs.com) for syntax highlighting, which works in tandem with fenced Markdown code blocks like so:

	```language-javascript
	var t = new Thing("Test!");
	```

Valid language classes include `language-markup`, `language-css`, `language-javascript`, `language-ruby`, and `language-php`. Prism.js supports a large range of additional languages (most of which have been included in Solar), as well as generic support for C-like languages.

![Syntax Highlighting Screenshot](http://i.imgur.com/yKQqTz1.png)


To-Do
-----

* The Jekyll version of Solar has linkblog support, while the Ghost one does not. This is because there isn't a finalized plugin API for Ghost yet, and there is no built-in linkblogging or post meta feature as of yet. This may change as Ghost's feature set is filled out more. (_Not investigated this change, section inharited from fork_)


License
-------

GPLv2 or higher
