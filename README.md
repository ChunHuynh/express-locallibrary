# express-locallibrary

## **Description**

Repository to follow along the [MDN tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs) for server-side website programming using Express(Node.js) web framework.
<br><br>
***LocalLibrary*** is the name of the website that we'll create over the course of the MDN tutorial. The purpose of the website is to provide an online catalog for a small local library, where users can browse available books and manage their accounts.
<br>

## **Overview**
In this series of tutorial we will:

- Use the *Express Application Generator* tool to create a skeleton website and application.
- Start and stop the Node web server.
- Use a database to store the application's data.
- Create routes for requesting different information, and templates ("views") to render the data as HTML to be displayed in the browser.
- Work with forms.
- Deploy the application to production.

## **Database**
For this project, we use a ***MongoDB*** database to access our library data.<br>
The cloud-hosted sandbox database ***MongoDB Atlas*** is used to set up the database.<br>
***Mongoose*** is used to connect and access the database as ODM in our code.
**<p align=center>UML diagram</p>**
![UML diagram](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/mongoose/library_website_-_mongoose_express.png)