# StandByMe-SC
We aims to create a communication app for foreign workers in Korea, providing them with a platform to communicate through message boards and interact with one another.

Utilizing Flutter, we developed an Android app for a foreigner community service For essential translation functionality specific to the foreign community app, we integrated Papago, and referenced libraries directly managed by Google to create the foreigner community service

Users proceed with social login via the Google login button on the application. Using the Firebase authentication token, user information is stored in the server's MySQL database.

The token issued in this manner is verified in Flutter to authenticate the user's identity, and the token is included in the request header to communicate with the server. Token validation is performed on the response to assist users in using the app.

After logging in, users can freely write and communicate through posts. I created a foreign community service on Android using Flutter.

The translation feature, essential for the app's foreign community characteristic, was developed using Papago, and the foreign community service was created by referencing libraries managed directly by Google.

For the backend, I primarily used Spring Boot to write detailed code, and the data received from the frontend is stored in the database through MySQL. Swagger was applied to Spring Boot for smooth communication with the frontend, and AWS EC2 and RDS were used for server deployment.
