Menu Trail by Path
==================

Menu Trail by Path allows you to set the active-trail on menu items according to
the current URL. You can also optionally set the breadcrumb trail to the same.

Consider the following scenario:  
You give your Post content type a URL pattern of `posts/[node:title]` and you
disable its menu settings. You then create a view for your posts and give it a
URL of `posts` and a link in the main menu.
With this module, when you visit `posts/my-first-post`, the Posts menu item will
have the active-trail class and (optionally) the breadcrumb trail will show:
Home > Posts.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

- Visit the configuration page under Administration > Configuration > System >
  Menu trail by path (admin/config/system/menu_trail_by_path) and enable/disable
  breadcrumb handling.


License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.


Current Maintainers
-------------------

- Seeking maintainer(s)


Credits
-------

- Ported to Backdrop CMS by [Peter Anderson](https://github.com/BWPanda).
- Originally written for Drupal by [Adam Moore](https://github.com/redndahead).
