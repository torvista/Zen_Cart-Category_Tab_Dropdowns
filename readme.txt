Category Tab Dropdowns
Plugin: https://www.zen-cart.com/downloads.php?do=file&id=1003
GitHub: https://github.com/torvista/Zen_Cart-Category_Tab_Dropdowns
License http://www.zen-cart.com/license/2_0.txt GNU Public License V2.0

Version 2

Function
The Category Tab Menu (Admin: Configuration->Layout Settings->Categories-Tabs Menu) displays the top categories as links in a list.
This mod adds the subcategories to those links.
It is a single level only so it will display subcategories or products depending on the category content.
Currently it will NOT list linked products (products that are not in their Master Category ID).
--------------------------------------------------------
DO NOT TEST ANYTHING ON YOUR PRODUCTION SERVER: use your development server.
--------------------------------------------------------
INSTALL/UPDATE
1. Uncompress the zip file on your computer.

2. Since responsive_classic SHOULD be unaltered from vanilla, you can test these files here first before duplicating them in your custom template.
Copy 
/includes/templates/responsive_classic/templates/tpl_modules_categories_tabs.php

If you already have an override copy of the tpl_modules_categories_tabs.php you’ll need to compare and merge the differences.

3. Copy 
/includes/templates/responsive_classic/css/tpl_modules_categories_tabs.php
 Edit as required to fit with your styles.
 
--------------------------------------------------------
Version History:
2.0 torvista
Fix for responsive_classic as example.

1.5.1 ray-the-otter
Applied patch found here http://www.zen-cart.com/showthread.php?181612-Category-Tab-Simple-Dropdown-Menu-1-3-9-Support-Thread&p=1088097#post1088097
to allow the Category sidebox to expand when selecting a sub-category from drop down menu. Thanks to gjh42 for his help in pointing this out!

1.3.9 dbltoe
Changed the code to remove nested <br /> coding in the tpl file and created a separate css file to properly display and validate the menu.

1.02a hem
Fixed bug that displayed products with status=0
Simplified the cPath construction for subcategories. No longer using zen_get_path(cat_id)

1.00a hem Andrew Moore
First release
