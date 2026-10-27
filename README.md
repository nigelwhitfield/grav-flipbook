# grav-flipbook
A simple example of adding an HTML 5 flipbook to Grav CMS, using StPageflip

This is a set of files that can be added to a Grav 2 theme to add a simple flip-book 
to your site.

It consists of a YAML blueprint, a JS file and and a twig template with some inline CSS.

Add the files to your theme directory, and you can then create a new page with template 'Edition'

Create image files for the flipbook, ideally named in numeric order, eg page_01.png,
page_02.png and so on, and drop them onto the media upload area for the page.

You can add introductory text above the flipbook, as seen in the demo (possibly NSFW) at
[subdirectory.uk/manumission/taster](https://subdirectory.uk/manumission/taster).

The actual JavaScript and CSS are from [St PageFlip](https://github.com/Nodlik/StPageFlip/releases), 
with the CSS slightly updated to set the width for my site to 80%.
