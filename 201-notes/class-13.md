# Local Storage
Persistnet local storage is one of the aread where native client applications have held an advantage over web applications.

Cookies were invented early in the web's history, and indeed they can be used for persistent local storage of small amounts of data. They have three major downsides.
1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

## HTML5 Storage
HTML5 STorage is a specification named Web Storage. Certain browser vendors also refer to it as local storage or DOM storage. HTML5 storage is a way for web pages to store named key/value pairs locally, within the client web browser.

### Using HTML5 Storage 
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.