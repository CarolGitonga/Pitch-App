# Pitch-App

## Author

[carol-profile](https://github.com/carol-profile)

# Description
This is a flask application that allows users to post one minute pitches and also allows other users who have signed up to comment and upvote or downvote a pitch. It also allows a person to signup to be able to access the functionalities of the application

## Live Link
[View Site]()

## Screenshot


## User Story

* Comment on the different pitches posted py other uses.
* See the pitches posted by other uses.
* Vote on s pitch they have viwed by giving it a upvote or a downvote.
* Register to be allowed to log in to the application
* View pitches from the different categories.
* Submit a pitch to a specific category of their choice.

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all posts, Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with app pitches based on categories and commenting section|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments tamplate with your comment and other comments|





## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
 git@github.com:carol-profile/Pitch-App.git
  ```
2. Move to the folder and install requirements
  ```bash
  cd Pitch-App
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3 manage.py server
  ```
5. Testing the application
  ```bash
  python3 manage.py test
  ```


## Technology used

* [Python3](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

Slack Profile - [Carol Gitonga](https://app.slack.com/client/T0101L740P4/D036H8B6WF2/user_profile/U0330AYGJAY)



## License
* *MIT License:*
* Copyright (c) 2022 **Carol Gitonga**

[Go Back to the top](#Pitch-App)
