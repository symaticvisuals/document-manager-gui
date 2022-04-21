# Document Mangement System
An application for managing the documents within the organization on different authority levels and arrangs them to solve the problem of finding the important documents. The application will deliver the Data Management, User Interface and Dashboard to interact with the application.

### Functions
- User Authentication using OAuth2
- Dashboard for different roles
- Profile for users (Optional)
- User Upload Tracking (Optional)

##### Database - Mongo DB
##### Frontend - Reactjs
##### Backend - Expressjs

### User Roles in Project
#### - Super Admin
- Assign user and the committee access and responsibility to the new users.
- Remove the user access to the above.
- Watch out the new users.
- Uptime of the users (Optional)
- Can see all the submissions according to the committee.


#### - Committee
- Can assign & remove responsibilities for the users.
- Can see the submissions of each responsibility.
- Assign task to a user (Optional)
- Lock time period of a submission. (Optional)
- Approve a submission. (Optional)

#### - User
- Can make a submission for the responsibility.
- Can edit the submission.
- Can view previous Submissions.
- Can Edit the previous submission before the lock time (Optional).
- Can see assigned responsibilities.

### Frontend Libraries Used
- React-Query ( For the API Calls from the backend )
- Material UI ( Structure the Application Theme )
- React-Router-Dom ( Routing within the Application )
- Redux-Toolkit ( State Management for the Application )
- Formik ( Form validations )

### Backend Libraries Used
- TBD