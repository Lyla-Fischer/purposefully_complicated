# purposefully_complicated
An app that is much more complicated than it needs to be - This was a funny plan, and I'll leave it up for humor's sake, but I don't know if/when I'm actually going to build the app.

Milestone 1: Hello World
===

(1) Make a simple front-end-only app that displays the traditional “hello world” message.

(2) Add a backend to the app, and fetch a hard-coded “hello world” message from the backend.

(3) Add a database to the app, with a single entry: “hello world”.

(4) Set up continuous deployment for this three-layered app, including a robust test suite and a staging site.

Milestone 2: Blinky Lights
====

(5) In addition to the string “hello world”, display an image of a light bulb which is stored on the web server

(6) Instead of storing the image of the light bulb on the web server, store it in an asset library.

(7) “blink” the light with a second image, only on the front-end, with the images cached.

(8) Update the image and make sure that the cache updates during development.

(9) Blink the light across devices in sync

(10) Remember which state the light was in when all clients have left the lighted site.

(11) Make it fault-tolerant

(12) Allow users to click the light in order to toggle its state. Make sure everything stays in sync across devices.

(13) Log all of the changes to the light, both automatic and manual.

Milestone 3: Auth
===

(14) Log in to blink the light

(15) Manage permissions to allow someone to blink the light or not

(16) Only prompt to log in if you try to blink the light

Milestone 4: CRUD
===

(17) Add new lights that can blink

(18) Choose the color of the svg image of the light
(18.1) Secure a user upload of a custom image.

(19) Delete a blinking light

Milestone 5: l10n
===

(20) Translate the “hello world” string.

(21) Display a localized datetime.

Milestone 6: a11y
===

(22) Make the app accessible to screen readers

Milestone 7: documentation
===

(23) Document all of the API endpoints (you know, in case anyone else wants to make a custom front-end)

Milestone 8: Cross-platform
===

(24) Make the app run on android, ios, and web

Milestone 9: Iterate!
===

(25) Add a feature and make sure nothing breaks!
-> Specifically, allow users to specify the rate at which the light blinks
