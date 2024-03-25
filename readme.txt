  Category Tab Simple Dropdown Menu
  Created by Andrew Moore 
  Version 1.02a
  License http://www.zen-cart.com/license/2_0.txt GNU Public License V2.0

--------------------------------------------------------

!!!BACKUP!!! ALWAYS MAKE SURE YOU HAVE AN UP TO DATE BACKUP OF YOUR FILES and MySQL DATABASE BEFORE INSTALLING

--------------------------------------------------------

INSTALL/UPDATE

1. Unzip the zip file into your Zen Cart root folder

2. Copy all the files in folders named 'custom' to your corresponding custom folders.

--------------------------------------------------------

SYNOPSIS

This mod adds a very simple CSS dropdown menu to the Category Tab. It is a single level only so it will display
subcategories or products depending on what the Category contains. Make sure your Category Tab Menu is switched 
on in Admin: 
	Configuration->Layout Settings->Categories-Tabs Menu

--------------------------------------------------------

Version History:

1.02a

Fixed bug that displayed products with status=0

1.01a

Simplified the cPath construction for subcategories. No longer using zen_get_path(cat_id)

1.00a

First release
