
4.13 Send Redirect in Servlet
-----------------------------
![2016-02-17 17](https://cloud.githubusercontent.com/assets/16971890/13106263/49088688-d58d-11e5-81e2-2ffd33314f72.png)
![2016-02-17 16](https://cloud.githubusercontent.com/assets/16971890/13106264/49491694-d58d-11e5-8163-5c8ceaf64c5f.png)

When we want that someone else should handle the response of our servlet, then there we should use sendRedirect() method.
In send Redirect whenever the client makes any request it goes to the container, there the container decides whether the concerned servlet can handle the request or not. If not then the servlet decides that the request can be handle by other servlet or jsp. Then the servlet calls the sendRedirect() method of the response object and sends back the response to the browser along with the status code. Then the browser sees the status code and look for that servlet which can now handle the request. Again the browser makes a new request, but with the name of that servlet which can now handle the request and the result will be displayed to you by the browser. In all this process the client is unaware of the processing.
In this example we are going to make one html in which we will submit the user name and his password. The controller will check if the password entered by the user is correct or not. If the password entered by the user is correct then the servlet will redirect the request to the other servlet which will handle the request. If the password entered by the user is wrong then the request will be forwarded to the html form.


