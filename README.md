# Google Calendar Material Design

Inspired by:
- [Ink for Google™](https://chrome.google.com/webstore/detail/ink-for-google/hmanckoiohnlgdommlcckcflkmllobgj)
- [cleanGoogleCalendar by @Gambloide](https://gist.github.com/Gambloide/a5ed244df001039bb7e4)

## Why?

1. Ink for Google did a great job at improving the Calendar design. But, it doesn’t touch the full interface.
2. CleanGoogleCalendar by @Gambloide improves the events layout.
3. I added CSS to improve some edit windows.

## How to use?

### Method 1: In browser (User CSS)

Download the Stylish extension (or any alternative):
 [Chrome](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Safari](http://sobolev.us/stylish/), 
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome), 
[Opera](https://addons.opera.com/extensions/details/stylish/)

Add this combined CSS with @import statements as a Custom Stylesheet for ‘calendar.google.com’:
https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/assets/css/google-calendar-material-import.css

### Method 2: Standalone Mac App - Download Fluid App
- Download [Fluid App](http://fluidapp.com) to transform any web page into a native Mac App.
- Pay for the license to enable ‘Userstyles’.
- Download the Google Calendar app icon: https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/assets/images/google-calendar-logo.png
- Create a standalone app for URL calendar.google.com named ‘Google Calendar’ and use the custom app icon.

FluidApp does not support @import statements. So you will have to manually add the CSS:

Edit your custom styles (**Window → Userscripts**) and add these separate stylesheets (hosted via RawGit):

1. Ink-For-Google: https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/src/ink-for-google/assets/stylesheets/calendar.css
2. cleanGoogleCalendar by @Gambloide: https://cdn.rawgit.com/Gambloide/a5ed244df001039bb7e4/raw/1c43c43715f3dca26b120d0f412bf5e9f59e9a6f/cleanGoogleCalendar.css
3. Extra CSS customisations by patrickplaggenborg: https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/assets/css/google-calendar-material.css

Or (easier) add the combined CSS stylesheet:
https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/assets/css/google-calendar-material-combined.css




Enjoy!

*I’m by no means a good coder (or architect of GitHub repositories) so any feedback to organise this is welcome*.
