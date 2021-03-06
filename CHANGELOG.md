# Change Log

Below you will find all the different changes that have been added since the first introduction of versioning for the bbUI toolkit.

## Version 0.9.1

* First version number provided for the toolkit
* Modified menus to require both a caption and an image for PlayBook 2.x and BlackBerry 10 to follow UX guidelines
* Image List item text will now add an Ellipsis "..." to the end of text that is too long for the list item on devices that support it
* Merged the Inbox style list into the Image List control
* Removed the tall list layout... This will be merging into a feature of the Image List in a upcoming release
* Added sub title text to the image list control
* JS and CSS files now renamed to match the toolkit version
* Updated all the samples to show how to handle BB10 color themes while supporting non-BB10 devices at the same time
* New **manditory bb.int(options)** function to initialize the toolkit allowing for overrides of properties and events
* bb.onscreenready has now been removed and added as an option for the bb.init() function
* New header item support for the image list
* New grid view for BlackBerry 10 
* New action bar for BlackBerry 10 with dark and light themes. Support for back button, highlight tabs, and action buttons
* New highlight and accent colors for BlackBerry 10
* New BlackBerry 10 button & pill button styling with dark and light themes
* New BlackBerry 10 swipe down menu styling
* New BlackBerry 10 Context Menu
* New BlackBerry 10 Press and hold Context Menu integration into Image Lists
* New BlackBerry 10 styled inputs with "delete" button and styled placeholder text
* Added screen and list coloring for BB10 with dark and light themes
* New **ondomready** event which fires after your screen has been loaded into the DOM
* Changed all of the isBB5/isBB6/etc functions to boolean properties. This avoids a scenario where these may evaluate to true simply because the function was assigned
* Sample: Added a fun random color changer for highlight and accent colors on BlackBerry 10
* Sample: Added BlackBerry 10 grid
* Sample: Added BlackBerry 10 action bar
* Sample: Grouped items on main menu screen
 