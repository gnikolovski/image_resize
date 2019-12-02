CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Installation
 * Configuration
 * Maintainers


INTRODUCTION
------------

Before downloading and using this module please read the next lines carefully.
This module has a very specific use case. You should not use it to resize images
that are managed by Drupal. If your content type or taxonomy vocabulary has an
image field, then images you upload to the nodes or terms of this type are most
likely managed by Drupal.

Use this module if your images are not managed by Drupal. Lets say that for some
reason you are loading images directly in templates, based on some file path
pattern, then these images "live" outside of Drupal. This usually happens when
you migrate from some other system and your images have a specific names, so you
can load them directly in template. "Image resize" will resize only images in a
specified folder, and it won't modify any table in your database.

 * For a full description of the module, visit the project page:
   https://www.drupal.org/project/image_resize

 * To submit bug reports and feature suggestions, or to track changes:
   https://www.drupal.org/project/issues/image_resize


REQUIREMENTS
------------

This module requires no modules outside of Drupal core. Just make sure that you
have at least PHP 5.5.0.


INSTALLATION
------------

 * Install the Image Resize module as you would normally install a contributed
   Drupal module. Visit https://www.drupal.org/docs/7/extend/installing-modules
   for further information.


CONFIGURATION
-------------

    1. Go to the module settings '/admin/config/media/image-resize/settings'
       page and set options for resizing you images.
    2. Go to the '/admin/config/media/image-resize' page and start resizing
       images.


MAINTAINERS
-----------

Current maintainers:
 * Goran Nikolovski (gnikolovski) - https://www.drupal.org/u/gnikolovski

This project has been sponsored by:
 * Studio Present - https://www.drupal.org/studio-present
