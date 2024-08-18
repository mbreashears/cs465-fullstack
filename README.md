# cs465-fullstack
CS-465 Full Stack Development with MEAN

Architecture


The Express HTML pages worked like a typical website in terms of displaying information and allowing the users to enter data and click links. The single-page application (SPA) contained all of the necessary data and functions on a single page and only displayed some options if the user was logged in. JavaScript was used for the functionality of both of these aspects. The backend uses a NoSQL MongoDB database to allow for the trips to be saved in a database as JSON documents to be used in both the Express website and the SPA. This is more efficient than trying to read them from the file system.


Functionality


JSON is derived from JavaScript, but there are differences between both. JSON allowed for organizing the data that we obtained from our JavaScript program. It also allowed us to tie together the frontend and backend development by allowing data to interact with multiple languages, such as HTML and JavaScript.

One instance where refactored codoe helped to improve funcitonality and efficiencies was with refactoring the code to allow for security to be implemented. One area where I benefited from in this was with reusable UI components. A lot of UI components were able to be reused, which saved time as it meant I did not have to waste time creating new components.


Testing


The main things that I tested to make sure they were working properly were the methods, the endpoints, and security. The methods were used to access the data at the endpoints, and security was used to authenticate these requests. I tested the methods by running the code, and I tested that data was properly going through the endpoints by checking MongoDBCompass and Postman. I tested the security by testing the methods for logging in and logging out and making sure the program was responding appropriately.

Reflection


I feel that this course has helped me in reaching my professional goals by exposing me to parts of development that previous courses did not. The most important skill I learned was using Git properly to create different branches at each stage of development. This course also helped me with learning more about how to work with NoSQL and MongoDB. It also helped with refreshing my skills as it relates to programming in general.
