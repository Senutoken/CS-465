# CS465 - Fullstack

In this course, I developed a MEAN full stack application following the lessons taught to us through our readings, lectures, and documents. I utilized Express for the back-end of the application, which had the role of taking in incoming requests from the client and handling information accordingly. Angular focused on handling the front-end requests of the user as well as manipulating the logic that occured on the front-end using the program's components. MongoDB was used as the database to store and retrieve information. JavaScript is the foundation of the language to handle to program's functionality. 

Below I answer some questions regarding the topic of this project, such as the architecture, funationality, testing, and a personal reflection.

# Architecture
This is the first time I've developed a program utilizing a front-end application such as Angular. Some of the similarities Angular has with Express HTML is that it handles the HTML files as a template to layout the user's interface side of the application. Single Page Applications (SPA) does a similar thing as well, although using a SPA has a more dynamic flow to it as we are able to load in our resources more quickly without the need to load everything at once. I believe the main reason for MongoDB being chosen as our database is because it is able to read from JSON objects which can be organized in our program. Unlike SQL that uses rows and columns, using a JSON stored data from a datastore or database is faster and can be narrowed down faster compared to a database that needs to sort through rows and columns.

# Functionality
JSON and Javascript are similar in that they both come from JavaScript. JSON is short for JavaScript Object Notation, but the main difference I see between the two is that JavaScript is mainly a programming language while JSON is used to communicate blocks or data objects between to points. JSON is not necessarily restricted to JavaScript, as MongoDB is also able to read and parse the data inside of it. With this, I believe JSON ties in both front and back-end development together as it is data used to communicate between the database and the front end. For instance, retrieving a username and password stored in a database; once the user enters their credentials, the front-end communicates with the back-end with the data (username and password). Depeneding on whether the JSON data was found, the information is sent back to either allow or deny access to the user logging in.
A resuable user interface (UI) is just as handy as reusable code, such is the case with some of the files in our application such as the handlebars we used. One instance of the UI being reused with slight modifications is when the client checks the trips page logged in or logged out. The page's are similar, showing updated information and the trip details. The big difference is that a logged in account would be able to modify and add additional trips while a logged account can only view the trips. Without having to recreate the HTML for the page each time, this is one case in which the UI is reused for different scenarios.

# Testing
Much of the testing performed in this application came from creating sample accounts and trips to see whether they registered correctly into the system. From my process, I encountered a lot of issues in which the program "broke" when a field was input incorrectly. Another kind of test I used a lot that I personally use for my own projects are the print statements to ensure the flow of logic is proceeding to plan. These prints can be found when the user is logging in or looking at the trips page. It tells me that the program was able to reach that stage without much issue. As for the security portion, I was only able to test this from the point of logging in. Using the correct username but incorrect password denied me entry into editing the trips and logging in. This was also the case for entering a random username in which the program gave me the same result.

# Reflection
I learned a lot of skills in this course and was exposed to a lot of new elements in programming. This is my first time handling front-end and back-end programming for a web application, as well as utilizing PowerShell and Visual Studio Code's terminal to execute terminal commands. I learned how to seed a database, understand the components of Angular and what each is responsible for, and understand for the most part the flow of logic in the application. Professionally, I think this class has given me a better understanding a grasp of the responsibilities and tasks a full stack developer needs to have to get the job done. It's exciting and there's a lot of avenues to make better optimizations and customizations to a program, so there's still a lot of room for me to learn and improve.

I will say, however, that with all this new information it was difficult for me to retain everything taught in the class. That is why I'd like to start working on my own web application with the skills I've learned to hone them and become a better Full Stack developer than I was this term.
