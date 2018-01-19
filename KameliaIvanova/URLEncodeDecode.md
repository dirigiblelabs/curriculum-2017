
# **URL encoding/decoding**


URL encoding, also known as Percent-encoding, is a mechanism for encoding information in a Uniform Resource Identifier (URI) under certain circumstances. Although it is known as URL encoding it is, in fact, used more generally within the main Uniform Resource Identifier (URI) set, which includes both Uniform Resource Locator (URL) and Uniform Resource Name (URN). As such it is also used in the preparation of data of the "application/x-www-form-urlencoded" media type, as is often used in the submission of HTML form data in HTTP requests.



## **Version 3.x**
Module: utils/v3/url
Alias: utils/url
Definition: https://github.com/eclipse/dirigible/issues/25
Source: /utils/v3/url.js
Facade: UrlFacade
Status: alpha

## **Basic Usage**

    var url = require('utils/v3/url');
    var response = require('http/v3/response');

    response.println(url.encode('<![CDATA[<meta http-equiv="refresh" content="0;url=javascript:document.vulnerable=true;">]]>'));
    response.println(url.decode('%3C%21%5BCDATA%5B%3Cmeta+http-equiv%3D%22refresh%22+content%3D%220%3Burl%3Djavascript%3Adocument.vulnerable%3Dtrue%3B%22%3E%5D%5D%3E'));

    response.flush();
    response.close();

## **Functions**
----------------------------------------------------------------------------------------
**decode(input)** - Decode an input string from application/x-www-form-urlencoded format. 

**encode(input)** - Encode an input string to application/x-www-form-urlencoded format.	

**escape(input)** - Escape an input string to comply to URI RFC 3986.	

-----------------------------------------------------------------------------------------
All of the above functions return string types.

### **Previous**
[Dirigible](Dirigible.md)
