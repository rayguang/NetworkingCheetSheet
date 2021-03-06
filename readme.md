### Difference between GET and POST
* GET request can be buffered; POST request not. If the request does not require to be buffered, use POST

* GET request sends both header and data together, server responses with 200 (fast?); POST request browser sends header first, server responses 100, browser then sends data, server responses 200 (reliable!). Exception is firefox which sends post header and request together. *However, this does not mean GET is faster than POST. If network condition is good, the difference is small.*

* GET appends request parameter in URL to get static info; POST appends request parameter in post body (more secure?), e.g., send sentive info. However, you can also appends data in body and you can capture the post body data anyway. 

Techinically, there is no fundamental difference between GET and POST and all depend on application scenario.

*Ref link: https://javarevisited.blogspot.com/2012/03/get-post-method-in-http-and-https.html*
