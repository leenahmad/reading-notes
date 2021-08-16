# localStorage

Window.localStorage
The localStorage read-only property of the window interface allows you to access a Storage object for the Document's origin; the stored data is saved across browser sessions.

localStorage is similar to sessionStorage, except that while localStorage data has no expiration time, sessionStorage data gets cleared when the page session ends — that is, when the page is closed. (localStorage data for a document loaded in a "private browsing" or "incognito" session is cleared when the last "private" tab is closed.)

Syntax
myStorage = window.localStorage;
Copy to Clipboard
Value
A Storage object which can be used to access the current origin's local storage space.

Exceptions
SecurityError
The request violates a policy decision, or the origin is not a valid scheme/host/port tuple (this can happen if the origin uses the file: or data: schemes, for example). For example, the user may have their browser configured to deny permission to persist data for the specified origin.
Description
The keys and the values stored with localStorage are always in the UTF-16 DOMString format, which uses two bytes per character. As with objects, integer keys are automatically converted to strings.

localStorage data is specific to the protocol of the document. In particular, for a site loaded over HTTP (e.g., http://example.com), localStorage returns a different object than localStorage for the corresponding site loaded over HTTPS (e.g., https://example.com).

For documents loaded from file: URLs (that is, files opened in the browser directly from the user’s local filesystem, rather than being served from a web server) the requirements for localStorage behavior are undefined and may vary among different browsers.

In all current browsers, localStorage seems to return a different object for each file: URL. In other words, each file: URL seems to have its own unique local-storage area. But there are no guarantees about that behavior, so you shouldn’t rely on it because, as mentioned above, the requirements for file: URLs remains undefined. So it’s possible that browsers may change their file: URL handling for localStorage at any time. In fact some browsers have changed their handling for it over time.



Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
What we really want is

- a lot of storage space
- on the client
- that persists beyond a page refresh
- and isn’t transmitted to the server



While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy.
As a web developer, that’s just not something you see every day, is it?
The Web SQL Database specification has been implemented by four browsers and platforms.
You need to say “the version of SQL that shipped with SQLite version X.Y.Z.” All of which brings us to the following disclaimer, currently residing at the top of the Web SQL Database specification: This specification has reached an impasse: all interested implementors have used the same SQL backend (Sqlite), but we need multiple independent implementations to proceed along a standardisation path.
An object store shares many concepts with a SQL database.
By contrast, Mozilla has stated that they will never implement Web SQL Database.)


[you can read more here](http://diveinto.html5doctor.com/storage.html)