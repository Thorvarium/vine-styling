# vine-styling

To change vine styles you can install a browser extensions that inject CSS for you automatically every time that a page load.

## PC
A popular one for desktop (PC) on chrome and firefox is called stylebot, but you can use any extension that supports css injection.
Install with the links below depending on your browser:

https://chrome.google.com/webstore/detail/stylebot/oiaejidbmkiecgbjeifoejpgmdaleoha?hl=en-US

https://addons.mozilla.org/en-US/firefox/addon/stylebot-web/

## Android
For Android, we recommend a browser called "Kiwi Browser", this browser supports extensions. 

Google chrome does not support extenions on android and firefox only have a limited quantity of extensions.

https://play.google.com/store/apps/details?id=com.kiwibrowser.browser&hl=en_US&gl=US

Inside kiwi browser you can install "Stylebot" as well

## iPhone
For iPhone, we recommend a browser called "Insight Browser", this browser supports extensions.

Safari does support extensions, but it also have a limit quantity.

Inside Insight Browser, go to settings and click on:
  -See all Extensions
  - Add a extension
  - Give it any name
  - Change the "IF" condition to: "url matches regex"
  - give it the value: ```^https:\/\/www.amazon.com\/vine```
  - change the "then" condition to "inject Css from URL"
  - use the url: ```https://raw.githubusercontent.com/Thorvarium/vine-styling/main/mobile/mobile.css```
