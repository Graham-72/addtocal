# Add to Cal

Provides an additional format for the display of date fields so that
they can be added into an external calendar. The types of calendar
available are:

* Google Calendar
* Yahoo! Calendar
* iCal
* Outlook

## Settings
1. Add a **date field** to the content type that provides the 
   calendar entry.
2. Open the date field's **display settings**.
3. Change the date field's format to be **Add to Cal**.
4. **Configure** the 'Add to Cal' detailed format settings.

* **Location Field**: An optional field to use as the location in calendar events.
* **Description Field**: An optional field to use as a description in calendar events.
* **Show for Past Events**: Determines whether the widget will be displayed for past events.

## Usage
The field formatter provides a button next to the field that shows a 
drop-down menu. This menu contains links to the supported formats, 
and includes basic styling that can be easily modified through CSS.

For screenshots and a more detailed explanation of how this module 
works, check out the blog post at 
http://thinkshout.com/blog/2012/06/kyle/add-to-cal

After installation, we recommend clearing your cache, or you may see 
a strange behavior where the .ics file downloads try to load as nodes 
rather than triggering a download. 
(/admin/config/development/performance)

## License

This project is GPL v2 software. See the LICENSE.txt file in this
directory for complete text.

## Credits

### Port to Backdrop

+ Graham Oliver (github.com/Graham-72)

### Maintainers for Drupal:
+ Andrei Colesnic (andrei.colesnic)
+ Greg Bloggs
+ Gabriel Carleton-Barnes (gcb)
+ Lev Tsypin (levelos)
+ Sean Larkin (seanberto)
