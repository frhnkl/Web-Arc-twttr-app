# Web Arc twttr app
This is a simple Twitter-like app created using Flask for the backend and Vue for the front end. The app allows users to register an account, log in, send tweets, upload pictures, and like other tweets. It also includes a leaderboard to track the number of tweets each user has posted. Additionally, there is an admin login to manipulate tweets, such as deleting and editing, as well as deleting user accounts.
# features
- User Registration: Users can create accounts with unique usernames and passwords.
- User Login: Registered users can log in securely.
- Posting Tweets: Users can post tweets with text and optional picture uploads.
- Liking Tweets: Users can like tweets posted by others.
- Leaderboard: A leaderboard displays the top users by the number of tweets posted.
- Admin Login: Administrators can manipulate tweets, delete tweets, and delete user accounts.
# Requirements and Technology Used
### backend
- Python
- Flask
- Flask-Admin
- Flask-Cors
- Flask-JWT-Extended
- Flask-Login
- Flask-SQLAlchemy
- psycopg2
- dotenv
- gunicorn
### frontend
- vue
- vue-router
- pinia
- axios
- datatables.net
- vue-sweetalert2
- tailwindcss

everything is available in both folders. requirement.txt for the backend and package.json for frontend
# User Guideline for Deployment
## Backend
- run flask-backend in the terminal and type
  ```cmd
  flask --app app run
  ```
  DB and backend side will be deployed with flask.
## Frontend
- run vue-frontend in the terminal and type
  ```cmd
  npm run dev
  ```
  vue will be running and you can click on the localhost link to use it. Frontend and Backend will automatically integrated.
