## Installation issues ##

**How do I install/use the library**

Please read the following blog post: to get started.

**The lib is not working**

Here are the main sources of problem:

  * Old version of the library: Foursquare now use OAuth so you need to upgrade your library
  * Old version of PHP: the library use the json\_decode function only available in PHP > 4.3 so make sure your
> Make sure you have a version of PHP > 5.2


## Authentication Issues ##

**How do I get my OAUTH token ?**

Got to [this page](https://elie.im/foursquare) to generate one.

**I lost my OAUTH token what can I do ?**

Just restart the generation procedure by going here:[this page](https://elie.im/foursquare), It will re-gnerate one.

**How do I remove the app access ?**

Got to your Foursquare settings and click on the remove button in the app setting for fq-php