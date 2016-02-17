
4.12 Time Updater in Servlet
----------------------------
![2016-02-17 12](https://cloud.githubusercontent.com/assets/16971890/13106216/171089aa-d58d-11e5-9b8f-f0e758b78025.png)
![2016-02-17 13](https://cloud.githubusercontent.com/assets/16971890/13106217/17204b56-d58d-11e5-81bb-5435953cdcc9.png)

In this program we are going to make one program on servlet which will keep on updating the time in every second and the result will be displayed to you.
To make this servlet firstly we need to make a class named TimeUpdater.  The name of the class should be such that it becomes easy to understand what the program is going to do. Call the method getWriter() method of the response object which will return a PrintWriter object. Use the method getHeader() of the response object to add a new header. We can also use setHeader() in place of getHeader(). The setHeader() method overrides the previous set header. Now by using the PrintWriter object display the result on the browser.


