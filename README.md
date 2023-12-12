ShortiFy:User Authentication:
1.	Signup Page:
    •	Collect user information, including email, name, and password.
    •	Validate and store user data securely in the database.
2.	Signin Page:
    •	Authenticate users based on their email and password.
    •	Direct users to the dashboard upon successful authentication.
Dashboard:
1.	Main Screen:
    •	Display a comprehensive list of all shortened URLs along with their corresponding QR codes.
    •	Provide a seamless user interface for effortless navigation.
2.	Create URL and QR Code:
    •	Implement a user-friendly form accessible from the dashboard to create new shortened URLs.
    •	Collect the original URL and a user-defined name for the link.
    •	Validate the uniqueness of the provided name and URL combination in the database.
    •	If the combination is unique, store the data in the database and return to the dashboard.
    •	Ensure that both the URL and its assigned name are unique for each user.
User Interface:
1.	Signup and Signin Pages:
    •	Design intuitive and responsive signup and signin pages for a smooth user onboarding experience.
2.	Dashboard Interface:
    •	Showcase all URLs and their QR codes on the main screen.
Database Integration:
1.	Mongoose Connection:
    •	Utilize Mongoose to connect and interact with the MongoDB database.
•	Implement secure storage for user data, link details, and QR code information.
Technology Stack:
   •	Backend: Node.js, Express.js
   •	Database: MongoDB (Mongoose)
   •	Frontend: HTML, CSS ,Java script
