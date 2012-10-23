Huntington Web Grid
===================

So named after the city of [Huntington, WV](http://goo.gl/maps/DOV2Q).

A huge-to-small 24 column responsive grid that follows [The Goldilocks Approach](http://goldilocksapproach.com/).

Design one, huge, .psd, plug it in to the framework in a couple hours, and make it responsive to any device in 10 minutes.

**[Demo Page](http://mscns.webfactional.com/huntington_web_grid/demo.html)**


Features
=

- 24 column responsive grid 
- [FontAwesome](http://fortawesome.github.com/Font-Awesome/) icons
- Built on [HTML5 Boilerplate](http://html5boilerplate.com/)
- Works in all major browsers


What this grid *isn't*
=

This grid is a really nice HTML5 responsive grid. It doesn't aim to be a one-size-fits-all solution like [Twitter Bootstrap](http://twitter.github.com/bootstrap/) and is geared towards designers rather than developers. If there are "goodies" like [gorgeous buttons](http://cssbutton.me/) or [elegant forms](http://twitter.github.com/bootstrap/base-css.html#forms) you like from other frameworks, feel free to tinker around for a bit and include them, but the scope of this project was to make a rock-solid CSS grid that stands out among it's peers, and I think it does it's job well.


Documentation
=

The demo.html should be pretty self-explanatory. Create big images (preferably vectors), put them in the CSS framework. It will do the rest all the way down to mobile. Once it's that small, you have to use the media queries included within style.css to hand-craft the mobile experience (which is usually as simple as setting an element's width to 100%).

I've zeroed out a lot of margins and paddings in huntington.css because I really hate the margins and paddings Normalize.css applies to a lot of elements.

The best workflow for this is:

1. Create beautiful vectors in Illustrator
1. Create a beautiful design in the biggest .psd (in the design folder) with your vectors and other huge-res images
1. Plug these images into the framework by referring back to the .psd ([ZenCoding](http://code.google.com/p/zen-coding/) is great for the markup)
1. Test out the responsiveness of your site by expanding/collapsing the width of your browser
1. Nitpick any descrepencies within the provided extra .psd's and style.css media queries
1. Once you get down to the smallest size, try setting elements to width:100% with a little margin-bottom. 90% of the time this will be enough.


To Do
=

- Create a screencast tutorial