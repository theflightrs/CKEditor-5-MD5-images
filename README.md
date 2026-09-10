CKEditor 5 MD5 images
=====================

Names inline images uploaded through the editor with an MD5 hash.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.


Usage
-----
Enable the module and use CKEditor 5 as intended.

**Optional:**

You can uncomment one of two hashing options in ckeditor_5_md5_images.module:
1) Option A: Hash of original filename + timestamp (guarantees uniqueness) (Default)
2) Option B: MD5 hash of actual file contents (great for deduplication)

After choosing one hashing option, go ahead and use CKeditor 5 as intended, uploading images (Drag & drop, or dialog). The images will be stored with their new MD5 hash file name on the server.

Documentation
-------------

Additional documentation is located in the wiki:
https://github.com/theflightrs/CKEditor-5-MD5-images/wiki


Issues
------


Bugs and feature requests should be reported in the issue queue:
https://github.com/theflightrs/CKEditor-5-MD5-images/issues


Current Maintainers
-------------------

- [RS Snyder](https://github.com/theflightrs)


Credits
-------

- Written for Backdrop CMS by [RS Snyder]([https://github.com/username](https://github.com/theflightrs)).



License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
the complete text.
