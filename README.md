# Adamant Analytics [![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

Adamant Analytics is a simple SSI script that tracks visitors using Google Analytics with disabled javascript and cookie.

SSI (Server Side Includes):  
* [wikipedia](https://en.wikipedia.org/wiki/Server_Side_Includes)
* [apache](http://httpd.apache.org/docs/current/howto/ssi.html)
* [tomcat](https://tomcat.apache.org/tomcat-7.0-doc/ssi-howto.html)
* [nginx](http://nginx.org/en/docs/http/ngx_http_ssi_module.html)
* [iis](https://www.iis.net/configreference/system.webserver/serversideinclude)

Configuration:
* `GA_ACCOUNT` - Google Analytics web-property ID;
* `LOCAL_GIF` - Path to local 'utm.gif' if needed;
* `VISITOR_UA` - Create visitor ID from User Agent string;
* `UTM_SOURCE` - Default 'utm_source' value;
* `UTM_MEDIUM` - Default 'utm_medium' value;
* `UTM_CAMPAIGN` - Default 'utm_campaign' value;
* `UTM_TITLE` - Default 'utmdt' value;
* `UTM_CHARSET` - Default document charset;
* `USE_NOSCRIPT` - Wraps with `<noscript>` tag.

For more information please visit [Adamant Analytics project page](http://datamart.github.io/Adamant/).
