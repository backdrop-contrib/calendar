# Calendar

This module will display any Views date field in calendar formats, 
including CCK date fields, node created or updated dates, etc. 
Switch between year, month, and day views. Back and next navigation 
is provided for all views. Much of the Calendar functionality comes 
from the Date module, part of core in Backdrop.

See also Date iCal (not yet ported to Backdrop), a project that 
contains code and features needed to either import or export dates 
using iCal feeds. The functionality that used to be in the 
Calendar iCal module has been moved into Date iCal.

Create a new calendar by using the calendar template for the desired
date field. See a link to create a view from a template at the top
of the Views listing page.

This is a port from the Drupal module of the same name. 

## Status

This is an initial incomplete port of the module, requiring further work
on the integral views.


## Installation

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.
  
  For a quick and easy start, install the Date Tools module, then use
  the Date Tools Wizard to create a content type with a date field
  and a calendar that displays that field, all in a single step!
  
  
## Configuration

- Configuration settings are at admin/config/content/calendar.


## Help & Documentation

See readme.txt for more information about this module.


## License

This project is GPL v2 software. See the LICENSE.txt file in this
directory for complete text.
    
        
## Porting to Backdrop

Initial porting: Graham Oliver (github.com/Graham-72/)
- I am not proposing to do more work on this so please feel free
to take over if you think it worthwhile.

## Credits

### Maintainers for Drupal:

- Ted Bowman (tedbow)
- Pieter Jonckiere (pjonckiere)
- Geert van Dort (geertvd)
- Yonas Yanfa (fizk)
- Karen Stevenson (KarenS)

### Maintainer for Backdrop

- none yet, and no release yet.


### Acknowledgement

This port to Backdrop would not, of course, be possible without all
the work done by the developer and maintainer of the Drupal module.
