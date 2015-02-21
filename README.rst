==================
tiao Pelican Theme
==================

A meticulously designed Pelican theme built with Bootstrap3.

Settings
--------

``DISPLAY_PAGES_ON_SIDE``
*************************

In addition to ``DISPLAY_PAGES_ON_MENU``, which gives you the
option to display pages on the top-right navigation menu, we
also give you the option to display pages on the sidebar by 
setting ``DISPLAY_PAGES_ON_SIDE``. For obvious reasons, if both
variables are set to ``True``, we will not display the pages
on both menus. Instead, we only display it on the top-right 
navigation menu.

+---------------------------+---------------------------+----------------------+
| ``DISPLAY_PAGES_ON_MENU`` | ``DISPLAY_PAGES_ON_SIDE`` |       Behavior       |
+===========================+===========================+======================+
| False                     | False                     | Not displayed at all |
+---------------------------+---------------------------+----------------------+
| False                     | True                      | Displayed on Sidebar |
+---------------------------+---------------------------+----------------------+
| True                      | False                     | Displayed on Menu    |
+---------------------------+---------------------------+----------------------+
| True                      | True                      | Displayed on Menu    |
+---------------------------+---------------------------+----------------------+
