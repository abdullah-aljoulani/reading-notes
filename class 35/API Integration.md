## API Integration

**Explain the different between a query string parameter and a path parameter**

Query string parameters and path parameters are both used in web URLs to pass information to a web server, but they serve different purposes and are structured differently.
* Path Parameters
Location: Path parameters are part of the URL path itself. They typically come after the base URL and are separated by slashes ("/").
Purpose: Path parameters are used to identify a specific resource or endpoint on the server. They often represent a hierarchy or structure within the URL.
* Query String Parameters
Location: Query string parameters are appended to the end of a URL and are preceded by a question mark "?". Multiple query string parameters are separated by ampersands "&".
Purpose: Query string parameters are used to provide additional data to the server for various purposes such as filtering, sorting, or configuring the request.

**What would our API URL with a path id parameter be given the following information**

http://our-site.com/v3/stuff/things

**We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**

Imagine you have a magical box, and this box can do all sorts of things, like tell you the weather, play your favorite songs, or even give you information about your favorite books. However, this magical box doesn't understand human language directly, so you need a special way to talk to it.