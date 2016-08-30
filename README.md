#**Colorizr** README


Colorizr is a simple gem that works in terminal to *colorize* strings.


##Summary

Custom ruby gem that modifies the string colors in terminal. The colors include:

* red
* green
* yellow
* blue
* pink
* light_blue
* white
* light_grey
* black

##Install


gem install colorizr-0.0.2.gem

You will need to add the following code to your ruby file (hint: usually in app.rb).

require 'colorizr'

##Usage


You can use colorizr to quickly change colors in terminal so your presentation is not monochromatic. 

###Class methods


String.colors # => returns an Array of all the colors included in this gem.

String.sample_colors #=> returns a sentence with each of the colors included in this gem.

###Examples

puts "This string is red".red

puts "This string is light_grey".light_grey



