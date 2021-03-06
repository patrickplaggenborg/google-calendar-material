# Google Calendar redesign with Material Design

Inspired by:
- [Ink for Google™](https://chrome.google.com/webstore/detail/ink-for-google/hmanckoiohnlgdommlcckcflkmllobgj)
- [cleanGoogleCalendar by @Gambloide](https://gist.github.com/Gambloide/a5ed244df001039bb7e4)

## Why?

1. Ink for Google did a beautiful job at improving the Calendar design. But, it doesn’t touch the full interface and is not extensible.
2. CleanGoogleCalendar by @Gambloide improves the events layout.
3. I added CSS to improve some edit windows.
4. Allow for easy extension of these changes until Google finally publishes a redesign... (Might be coming soon: https://www.reddit.com/r/google/comments/6tl9ju/new_upcoming_google_calendar_desktop_ui/)

## How to use? Method A: In browser (User CSS)

![browser-icons]

1. Download the [Stylish](https://userstyles.org) extension for  [Chrome](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Safari](http://sobolev.us/stylish/), 
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome) or  [Opera](https://addons.opera.com/extensions/details/stylish/) (or use any other extension to inject custom CSS)

2. Add the contents of this combined CSS as a Custom Stylesheet for ‘calendar.google.com’:
https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/assets/css/google-calendar-material-combined.css

## How to use? Method B: Standalone Google Calendar Mac App (using Fluid)

![app-icon]

1. **Download [Fluid App](http://fluidapp.com) to transform any web page into a native Mac App.**

  * Pay for the license to enable ‘Userstyles’.
  * Download the Google Calendar app icon: https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/assets/images/google-calendar-logo.png
  * Create a standalone app for URL calendar.google.com named ‘Google Calendar’ and use the custom app icon.

2. **Add the Combined CSS for Google Calendar Material Design to the Custom Styles:**

   Edit your custom styles (Window → Userscripts) and add the contents of this stylesheet (hosted via RawGit):

  * https://cdn.rawgit.com/patrickplaggenborg/google-calendar-material/master/assets/css/google-calendar-material-combined.css


## Enjoy!

*I’m by no means a good coder (or architect of GitHub repositories) so any feedback to organise this is welcome*.

[browser-icons]: https://raw.githubusercontent.com/patrickplaggenborg/google-calendar-material/master/assets/images/browser-icons.png "Browser Icons"
[app-icon]: https://raw.githubusercontent.com/patrickplaggenborg/google-calendar-material/master/assets/images/google-calendar-logo-300.png "App Icon"



## Credits

Consider donating:
- [Ink for Google™](https://chrome.google.com/webstore/detail/ink-for-google/hmanckoiohnlgdommlcckcflkmllobgj) by [Carlos Jeurissen](https://carlosjeurissen.com/)
- [cleanGoogleCalendar](https://gist.github.com/Gambloide/a5ed244df001039bb7e4) by [@Gambloide](https://gist.github.com/Gambloide)
- Browser icons made by: [Pixel perfect](http://www.flaticon.com/authors/pixel-perfect) from www.flaticon.com and is licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/ "Creative Commons BY 3.0") 
- The Google Calendar name and logo are owned by Google.
