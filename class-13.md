## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS:

* Persistent local storage is one of the areas where native client applications have held an advantage over web applications.

* Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

* In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end.
* userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. 

* In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects.

* In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers. 
* By 2009, dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.
`Question` what is HTML5 Storage?

`Answer` it’s a way for web pages to store named key/value pairs locally, within the client web browser.

`Question` Which browsers? 

`Answer`  the latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer!

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 

* If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.




