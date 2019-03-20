# ADD
ADD - Alert Driven Development

## Overview
It's really simple, this concept is based on Browser Alerts, which you can easily dispatch with a single line code, like: `alert("hello user, my old friend")`  

## Definitions
An alert box is often used if you want to make sure information comes through to the user.
Note: The alert box takes the focus away from the current window, and forces the browser to read the message.

Ref: [W3Schools](https://www.w3schools.com/jsref/met_win_alert.asp)

The alert dialog should be used for messages which do not require any response on the part of the user, other than the acknowledgement of the message.
Dialog boxes are modal windows - they prevent the user from accessing the rest of the program's interface until the dialog box is closed.

Ref: [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert)

## Why ?
* It's simple to use
* User interaction
* You can guarantee that user read it
* Has no hack (Users cannot use console, erase html stuff to see something below of common modals or even click everywhere)
