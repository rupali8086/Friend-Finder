# Friend-Finder
 "FriendFinder" application -- basically a dating app using Express js 
 This is Full stack app.
 Deploy on  : Heroku

Structure :
```
├── app

|  ├── data

|  |  └── friends.js

|  ├── public

|  |  ├── home.html

|  |  └── survey.html

|  └── routing

|     ├── apiRoutes.js

|     └── htmlRoutes.js

├── package.json

└── server.js
```

 ** The basic npm packages used in class:  **
 express, body-parser and path

The functionality is pretty simple. 
There is a simple home page that points to the survey page. The survey has 12 questions. When it is submitted, the total score is compared with other people's total scores and a modal is shown with the greatest compatible person (the person with the closest total score). If there are not enough people to make a comparison, the user will be notified. 
If the form is not completed appropriately, the user will be notified.

## Author : 
Rupali Meshram
