==================
Tiao Pelican Theme
==================

A meticulously designed Pelican theme built with Bootstrap3.

Settings
========

The Tiao pelican theme honors the following Pelican settings:

* ``GOOGLE_ANALYTICS``

It also introduces the following settings

* ``DISPLAY_PAGES_ON_TOP`` (Default: ``False``)

  In addition to ``DISPLAY_PAGES_ON_MENU``, which gives you the
  option to display pages on the top-right navigation menu, we
  also give you the option to display pages on the sidebar by 
  setting ``DISPLAY_PAGES_ON_SIDE``. For obvious reasons, if both
  variables are set to ``True``, we will not display the pages
  on both menus. Instead, we only display it on the top-right 
  navigation menu.

  +-----------------------+----------------------+------------------------+
  | ``DISPLAY_*_ON_MENU`` | ``DISPLAY_*_ON_TOP`` |        Behavior        |
  +=======================+======================+========================+
  | False                 | False                | Not displayed at all   |
  +-----------------------+----------------------+------------------------+
  | False                 | True                 | Displayed on Top Menu  |
  +-----------------------+----------------------+------------------------+
  | True                  | False                | Displayed on Side Menu |
  +-----------------------+----------------------+------------------------+
  | True                  | True                 | Displayed on Side Menu |
  +-----------------------+----------------------+------------------------+

* ``DISPLAY_MENUITEMS_ON_MENU`` (Default: ``False``)

  Similar to ``DISPLAY_PAGES_ON_MENU``. Introduced to provide 
  options for placement of menu items.

* ``DISPLAY_MENUITEMS_ON_TOP`` (Default: ``False``)

  Similar to ``DISPLAY_PAGES_ON_TOP``.

License
=======

The MIT License (MIT)

Copyright (c) 2015 Louis Tiao

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
