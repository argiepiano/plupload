#  Plupload

This module integrates the Plupload library (available from http://plupload.com)
with Backdrop forms.

This is a port from the Drupal module of the same name, version 7.x-1.7

## Status

This is an initial port of the module ready for testing.

## Features

  - Supported Fields: Image, File
  - Integration of plupload for file-uploads
      (Works in almost every browser and device!)
  - Batch entity creation (Fill out one form, the batch process will do the rest)
  - Overview page for generated nodes (Mostly like admin/content/node)
  - Pathalias integration (Settings for a node type will be used)
  - Choose default values (The other fields assigned to the selected bundle
       (node type, taxonomy vocabulary) will be displayed with the selected widgets
        and you may add some default values)
  - Tokens integration for titles (Choose from user, node, file, date and
    many more tokens)


## Installation

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- To install the Plupload library:

  1. Download it (version 1.5.1.1 or later) from
     https://github.com/moxiecode/plupload/releases **Versions 2.x and 3.x
     are currently unsupported**. Latest 1.x.x version is 1.5.8, which can be
     downloaded from https://github.com/moxiecode/plupload/archive/v1.5.8.zip.
  2. Unzip it into sites/all/libraries, so that there's a
     sites/all/libraries/plupload/js/plupload.full.js file, in addition to the
     other files included in the library.
  3. Remove "examples" folder from libraries folder as it could constitute a
     security risk to your site. See http://drupal.org/node/1895328 and
     http://drupal.org/node/1189632 for more info.
  


## Help & Documentation

See readme.txt for more information about the background to
this module.


## License

This project is GPL v2 software. See the LICENSE.txt file in this
directory for complete text.
    
        
## Current porting to Backdrop

- Graham Oliver (github.com/Graham-72/)
- JF (github.com/gifad)

## Maintainers for Backdrop

- Seeking a maintainer

## Credits

### Maintainers for Drupal:

- budalokko
- Janez Urevc (slashrsm)
- Murat Günana (muri)
- Justin Ellison (justintime)
- David Rothstein (David_Rothstein)

Development of the Drupal module is supported by PhpStorm.


### Acknowledgement

This port to Backdrop would not, of course, be possible without all
the work done by the developer and maintainer of the Drupal module.
