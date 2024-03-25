  Category Tab Simple Dropdown Menu
  Created by Andrew Moore
  Modified by dbltoe 6/2011
  Version 1.3.9
  License http://www.zen-cart.com/license/2_0.txt GNU Public License V2.0

--------------------------------------------------------

!!!BACKUP!!! ALWAYS MAKE SURE YOU HAVE AN UP TO DATE BACKUP OF YOUR FILES and MySQL DATABASE BEFORE INSTALLING

--------------------------------------------------------

INSTALL/UPDATE

1. Unzip the zip file in a folder on your computer.
2. If you have a copy of the tpl_modules_categories_tabs.php already in a custom/override directory, download it to your computer and use a program like winmerge to compare/merge the two.
3. Use ftp to load the resulting tpl_modules-categories.php to your includes/templates/CUSTOM/templates directory and the catTabsMenu.css file to includes/templates/CUSTOM/css directory.  NOTE:  If you are using the classic template you may need to create a templates folder before uploading the tpl file.  Also, using the classic template will result in this file probably being overwritten on update. 
4. Adjust the settings in the catTabsMenu.css to change the look of the menu.

--------------------------------------------------------

SYNOPSIS

This mod adds a very simple CSS dropdown menu to the Category Tab.
It is a single level only so it will display subcategories or products depending on what the Category contains.
Currently it will NOT list products that are linked to a Master Category ID.
It is recommended that the embeddded style calls in the tpl file be moved to the stylesheet and removed from the tpl so that the HTML can validate.

Make sure your Category Tab Menu is switched on in Admin: 
	Configuration->Layout Settings->Categories-Tabs Menu

--------------------------------------------------------

Version History:

1.3.9

Changed the code to remove nested <br /> coding in the tpl file and created a separate css file to properly display and validate the menu.

1.02a

Fixed bug that displayed products with status=0

1.01a

Simplified the cPath construction for subcategories. No longer using zen_get_path(cat_id)

1.00a

First release
