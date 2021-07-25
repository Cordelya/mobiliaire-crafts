# Mobiliaire for Crafts
A lightweight Craft Supplies and Tools inventory helper

## This repository has moved to GitLab. Please visit [Cordelya's GitLab](https://gitlab.com/cordelya) and you'll find the active project there.

> mobiliaire (n.): Middle French form of "mobiliary"; pertaining to furniture or movable property

*built for/on Django 3.1*

This self-hosted app is a fork of [Mobiliaire](https://github.com/Cordelya/mobiliaire)

Want to try it out? 

````
$ git clone https://github.com/Cordelya/mobiliaire.git
````
[See a more detailed procedure.](https://github.com/Cordelya/mobiliaire/wiki/getStarted)

Inventory Items are grouped into Boxes (which can be literal or virtual boxes), which are then further grouped into Warehouses. In this context, a warehouse is a geographic location where a box or boxes are stored. A closet full of items is a Warehouse. 

# Unique Features
This README will only cover features that are unique to this fork. Please also see the main Mobliaire repository for a full feature list.

(I/N) = Implemented, Not Implemented (Yet)

* (N) Binary flags: is_pattern and is_yardage to allow for some major item-type differentiation.
* (N) Photo support for Pattern envelopes: set the pattern front photo as your main item photo, and insert the envelope rear photo into the appropriate field. Click on a pattern front image in the gallery and a javascript modal will pop up with the envelope reverse.
* (N) Pattern publisher and numbering support: For items which are patterns, additional optional fields are available allowing you to record the pattern's publisher, pattern number, and year of publication (because commercial pattern manufacturers reuse pattern numbers). Pattern Manufacturers are FK related to prevent spelling differences that could improperly exclude records in search results. If pattern count > 0, separate pattern count and value totals will be displayed where system totals are displayed.
* (N) Support for yardage: Quantity allows partial amounts. If total fabric yardage is > 0, separate yardage and value totals will be displayed where system totals are displayed.

This app is built on the well-established and well-documented Django framework. If you're not sure how to do something, try checking the Django documentation pages first.

# Changelog #
## Mobiliare for Crafts forked from Mobiliaire 1.0.1 on November 12, 2020

* Please see the main Mobiliaire repository for history beyond this point.
