# sharingfile
The file-sharing system is built using the Django Rest Framework and relies on a MySQL database. It ensures secure file exchange functionalities tailored for two distinct user roles. In the implementation, I've devised REST APIs to facilitate the subsequent actions for each user category:

Ops User (User 1) Actions:

Login:

Authentication process tailored for Ops Users.
Upload File:

Restricted to Ops Users; permits the upload of files limited to pptx, docx, and xlsx formats.
Client User (User 2) Actions:

Sign Up:

Generates and returns an encrypted URL upon successful registration.
Email Verify:

Initiates the sending of a verification email to the user's registered email for email confirmation.
Login:

Authentication mechanism designed for Client Users.
Download File:

Enables Client Users to download files.
List all uploaded files:

Presents a comprehensive list of files uploaded by Ops Users.
