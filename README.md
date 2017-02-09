Website Inaccessibility Test Lists
==================================

This repository is a collection of lists of URLs intended to estimate the accessibility or inaccessibility of different types of content from different countries.

The [Internet Monitor](https://cyber.harvard.edu/research/internetmonitor) project at the [Berkman Klein Center](https://cyber.harvard.edu/) is in the midst of a broad update of testing lists. The existing corpus of testing lists were originally put together by experts around the world for the [OpenNet Initiative](https://opennet.net/). While the OpenNet Initiative ceased operations in late 2014, the URL test lists generated for the project have been [hosted](https://github.com/citizenlab/test-lists), maintained, and updated by [Citizen Lab](http://citizenlab.org/). In an effort to merge Berkman Klein's updates and Citizen Lab's updates, the following rules are being followed:
* For a given country, if Berkman Klein has an updated list:
  * Include all URLs from the Berkman Klein list
  * If Citizen Lab also has a list, add URLs with a date_added field after 2014-04-15 (the minimum date present in the lists)
* If Berkman Klein does not have an updated list:
  * Include all Citizen Lab URLs
* Ensure all URLs are unique and normalized

Each list gives one or more categories for each URL as category codes. The meaning of these codes is given in category_codes.csv.

Some lists are for groups of country, e.g. "mena" (Middle East / North Africa). These groups and their country members are given in country_groups.csv
