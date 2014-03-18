ajax_region
===========

This module allows to configure flexibly the internal links of your site, which
will update the appointed regions using Ajax, instead of full page refresh.
Using this module you can configurate the usual ajax-menu without writing no
line of code.


It includes all the best of the modules:
Ajax Regions (https://drupal.org/project/ajax_regions) and
Ajax Nodeloader (https://drupal.org/node/1447164)


All the options are collected on one page of module configuration.
(admin/config/system/ajax_region)
You have to set js-object with list of regions (column REGION) to links with
certain selectors (column LINK), - which have to be updated by click.
The js-object is specified as a:
{region_name1: 'region-selector-1', region_name2: 'region-selector-2' ... }


Furthermore you can watch in options such additional parameters as:
SET LOADING-INDICATOR - imitation of indicator of loading the page by the
browser
UPDATE DOCUMENT TITLE - renewal title page
UPDATE CURRENT ADDRESS - the name speaks for itself
UPDATE ACTIVE LINKS - setting to new link class = "active" (this class is used
in menu of the theme appearance Bartik)


Besides, you have got the possibility to indicate your own js-functions
Drupal.ajax_region.before and Drupal.ajax_region.after, that will be executed
in accordance - before and after loading of ajax-content. Clear these fields,
if you don't want the functions to be generated on the pages of your site.
