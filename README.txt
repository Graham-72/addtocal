# Provides a widget containing links for exporting events to:

* Google Calendar
* Yahoo! Calendar
* iCal
* Outlook

Currently only works with nodes, but will soon be extended to other entity types.

A configuration process in in the works, but in the mean time, the module relies
on the following 3 variables, which can be set in the usual ways, including
settings.php, database, drush, install profile, etc.
* addtocal_node_types: array of node types the widget should be included for.
* addtocal_date_field: name of the date field.
* addtocal_location_field: name of the location field.

The module assumes that 'body' is used for the event description.
