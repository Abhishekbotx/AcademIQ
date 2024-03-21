# AcademIQ Edtech Web Application[Backend] 💻

AcademIQ an Edtech Web Application

AcademIQ is a robust edtech web application aimed at providing a comprehensive platform for online learning. <br>
It encompasses various features such as course management, user authentication, payment integration, and more, <br>
to create an immersive learning experience for users.

## Setting Up the Project

To set up the AcademIQ edtech web application locally, follow these steps:

**1. Clone the Repository:**

   ```
   git clone https://github.com/Abhishekbotx/AcademIQ/
   ```
**2. Install Dependencies**
    Navigate to the project directory and install the required dependencies using npm:
```
npm install
```
**3. Set Environment Variables:**

   Create a .env file in the root directory of the project and add the necessary environment variables
```
PORT=<your_port_no eg:3000>
MONGODB_URI=<your-mongodb-url>
CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
CLOUDINARY_API_KEY=<your-cloudinary-api-key>
CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
RAZORPAY_KEY_ID=<your-razorpay-key-id>
RAZORPAY_KEY_SECRET=<your-razorpay-key-secret>
```
**4. Start the Server:**

Run the following command to start the server:
```
npm start
```




## Libraries/Dependencies :

The AcademIQ edtech web application utilizes a variety of libraries and dependencies to facilitate its functionalities:

`bcrypt`: Utilized for securely hashing passwords, ensuring user data security.<br>
`cloudinary`: Integrated for seamless file uploading and management in the cloud, <br>enabling efficient handling of course materials and user uploads.<br>
`cookie-parser`: Middleware employed for parsing cookies in Express, enhancing session management capabilities.<br>
`cors`: Middleware utilized for enabling Cross-Origin Resource Sharing (CORS) in Express, <br>allowing the application to interact with resources from different origins.<br>
`crypto-random-string`: Utilized for generating cryptographically secure random strings, <br>ensuring uniqueness and security in token generation and other functionalities.<br>
`dotenv`: Employed for loading environment variables from a .env file, facilitating configuration management and environment-specific settings.<br>
`express`: Framework utilized for building web applications in Node.js, providing robust features for routing, middleware, and HTTP utilities.<br>
`express-fileupload`: Middleware utilized for handling file uploads in Express, enabling efficient handling of<br> user-submitted files such as profile pictures and course materials.<br>
`jsonwebtoken`: Utilized for generating and verifying JSON Web Tokens (JWT) for user authentication,<br> enabling secure and stateless authentication mechanisms.<br>
`mongoose`: MongoDB object modeling tool for Node.js, providing a straightforward schema-based solution for interacting with MongoDB databases.<br>
`node-schedule`: Employed for scheduling tasks in Node.js, enabling the application to perform automated<br> actions such as sending reminder emails or generating reports at specified intervals.<br>
`nodemailer`: Module utilized for sending emails in Node.js, enabling communication with users <br>through email notifications for account-related events such as password resets and course enrollments.<br>
`otp-generator`: Utilized for generating one-time passwords (OTPs), enabling secure authentication<br> and verification processes, especially for features like two-factor authentication.<br>
`razorpay`: Integrated for payment gateway integration, enabling secure and seamless processing<br> of online payments, including course enrollments and purchases of digital products and services.<br>

