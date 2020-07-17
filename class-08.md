# Local storage is pretty cool

Nontrivial applications have to store data somewhere, if a trip to a server has to be made each time data is read or written applications can slow down.

Cookies don't store enough data and are sent with every request. This will slow down your application and potentially cause security issues.

Lots of different companies attempted to make their own solutions to this. Some developers made libraries that would try to make things work across browsers, they worked but weren't ideal, eventually there was a standard created to clean up the mess.

Now it's all rainbows :rainbow:	 and unicorns :unicorn:. Modern(As of 2009) browsers all support local storage.

## The internet of strings

Local storage can store any data type as long as it's a string. Fortunately there are methods to convert Javascript objects to and from strings.

Limited to 5 mb