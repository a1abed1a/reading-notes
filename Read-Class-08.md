# APIs

1) What does REST stand for?  
**Representational State Transfer**

2) REST APIs are designed around a ____.  
**Resources**

3) What is an identifer of a resource? Give an example.  
**It's a URI that uniquely identifies that resource. For example, the URI for a particular customer order.**

4) What are the most common HTTP verbs?  
   - **GET**
   - **POST**
   - **PUT**
   - **PATCH**
   - **DELETE**

5) What should the URIs be based on?  
**should be independent and may occur in any order, so keeping transient state information between requests is not feasible.**

6) Give an example of a good URI.  
**https://adventure-works.com/orders**
7) What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  
**Expose a large number of small resources, and it is bad.**

8) What status code does a successful `GET` request return?  
**Returns HTTP status code 200 (OK).**

9) What status code does an unsuccessful `GET` request return?  
**Return 404 (Not Found).**

10) What status code does a successful `POST` request return?  
**Returns HTTP status code 201 (Created).**

11) What status code does a successful `DELETE` request return?  
**Respond with HTTP status code 204 (No Content).**
