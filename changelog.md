== v0.9 20/03/2014 by John Yin
- remove auto scroll bar in Contact Form
- show related product img on their original size  
- imprvoe product list format
- set fixed height (500px) for Privacy Policy colorbox when register
- fix snippet js get slideshow window height 
- all table title (with background) has #AAA
  all table title (no background) has #999


== v0.8fixed 19/03/2014 by John Yin
- scroll bar when Product Comparision, Account >> Transaction
- get current window width for colorbox when in 'register.tpl', 'slideshow.tpl', and for nivo_slide_container in 'product.tpl'.
- add '.wrapper' style for '#notification'
- unify all table header's font: normal size and light color

== v0.8 16/03/2014	by John Yin
stylesheet.css		
- move sw style into sw.css and move change log info
- change all heavy weight style to normal style
- unified hover effect (to #382eee) on links

responsive.css		
- move sw style into sw-responsive.css
- move change log info

jquery.elevatezoom.js	
- use jquery.elevatezoom.js to come true product main picture zoom. But side effect to small size window.

slideshow.tpl
- auto read picture size through file name to come true auto adjust the size of nivoSlide container
- jquery.colorbox.js (v1.5.5)
- Opencart default use v1.3.19 (of 2006)， begin to use this new version, but still need more test
							  
As for SW:
in extension: custom-content-module
- come true social media and shops contact information
- come true Testimonials

font-awesome
- begin use font-awesome in shops contact information

carousel.tpl
- custom carousel prev/next button and newest jCarousel.js still need more test


== v0.7 11/03/2014	by John Yin
stylesheet.css		
- related products: 20% thumbnail = 150px, as well updating
- system >> settings >> imgage >> related products
- 150px width of Specials/Latest/Features images at
- extension >> modules >> Specials/Latest/Features
- + google font: 'Droid Sans', 'Pontano Sans'

== v0.6 05/03/2014	by John Yin
responsive.css
- body mini-width: 300px
- responsive inputs when < 980px
- vertical #tabs when < 640px

== v0.5 25/02/2014 by John Yin
*.tpl: 
- remove all version logs from tpl files, for these would cause many issues, particularly for IE 9-, for IE knows comments tags: <!-- -->

header.tpl: 
use downlevel-revealed conditional comments in header.tpl, so as only loading responsive.css when !IE or IE 9 +

return_form.tpl:	
add this module and remove $(colorbox).colorbox snippet for running js error: $(...).colorbox is not a function

**	v0.5 support IE 9 (being tested by IE TESTER), except user account module.