# LOCAL STORAGE FOR WEB APPLICATIONS

## For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention.


- Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

1.  Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


# HTML5 STORAGE
***HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.***

***The most of the action resides in the string you pass to the executeSql method. This string can be any supported SQL statement, including SELECT, UPDATE, INSERT, and DELETE statements. It’s just like backend database programming.***