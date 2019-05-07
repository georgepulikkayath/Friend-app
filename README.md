# Friend-app
*There is two html pages are on this program.One is **home.html and other one is survey.html.The user can interact with this pages.**
*I created a folder named routing which is used to save the routhing files.**htmlRoutes.js-is used to load the html files and apiRoutes.js-is used to add a new friend by a post request also it gives the data as json**.
*server.js-is used for the server and routing.
##Dependencies
**express-used for routing**
**body-parser-parse http request body**
**path-The Path module provides a way of working with directories and file paths.**
###Main-Logic
*If someone want to go for a new survey it takes their information through survey.html file.
*Then it stores the new users's score in to a variable
*After that it comapres the score of the first friend in the api list with the the new user's score by a mathematic function **Math.abs**
*Store that differnce in to a variable.
*if the differnce is less than the best match(**it should be a predefined value**).Then the new user will be the best match and it contiues and find the best friend.
####Heroku
*This application is deployed in heroku.

