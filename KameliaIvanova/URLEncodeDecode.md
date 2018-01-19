
# **Encoding and Decoding URLs**


URL encoding, also known as Percent-encoding, is a mechanism for encoding information in a Uniform Resource Identifier (URI) under certain circumstances. Although it is known as URL encoding it is, in fact, used more generally within the main Uniform Resource Identifier (URI) set, which includes both Uniform Resource Locator (URL) and Uniform Resource Name (URN). As such it is also used in the preparation of data of the "application/x-www-form-urlencoded" media type, as is often used in the submission of HTML form data in HTTP requests.


## **Steps**
1. Open the Eclipse Dirigible page: http://www.dirigible.io/.
2. Create a new project. Add a .js file to your project.
3. Open the Eclipse Dirigible™ API on this page: http://www.dirigible.io/api/utils_url.html
4. Copy the code from the field **Basic Usage**. Paste the code in the .js file.
5. Save the changes by opening the **File** menu and choosing **Save All**.
6. With right-click on the mouse choose **Publish**.
7. Refresh the **Preview** window and see the result.

## **Functions Explanation**
----------------------------------------------------------------------------------------
**decode(input)** - Decode an input string from application/x-www-form-urlencoded format. 

**encode(input)** - Encode an input string to application/x-www-form-urlencoded format.	

**escape(input)** - Escape an input string to comply to URI RFC 3986.	

All of the above functions return String types.

