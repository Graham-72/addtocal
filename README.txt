Provides a widget containing links for exporting events to:

* Google Calendar
* Yahoo! Calendar
* iCal
* Outlook

## Usage
1. Open the widget's field display settings
2. Change the date field's format setting to _Add to Cal_

## Settings
All settings are set in the field formatter settings in _Manage Display_ for the selected entity type.
### Location Field
You can optionally choose a location field in the format settings view. This option will choose which of the entity's fields will populate the location value for calendar export.

### Show for Past Events
Determines whether the widget will be displayed for past events.

## Caveats
Currently only works with nodes, but will soon be extended to other entity types.

The module assumes that 'body' is used for the event description.
