Compatibility-based "FriendFinder" application. 
This site helps find friends (aka dating app) by taking inputs(from a survey) from users and matching it up with other user inputs. 

Survey consistes of 10 questions - response is scaled from 1 to 5 based on 'AGrees' or 'Disagrees'.

It compares answers with those from other users. The app will then display the name and picture of the user with the best overall match.

The server.js file utilizes the npm packages: express and path.
other npm packages: body.parser

The htmlRoutes.js file contains two routes:

A GET Route to /survey which displays the survey page.
A default, catch-all route ('/') that leads to home.html which displays the home page.
The apiRoutes.js file contains two routes:

A GET route with the url /api/friends. This is used to display a JSON of all possible friends.
A POST routes /api/friends. This is used to handle incoming survey results. This route is also used to handle the compatibility logic.
Application data is saved inside of app/data/friends.js as an list of objects.

App alos needs to be depoyed to Heroku:
 Deployed Herok Link:
 https://powerful-bayou-16331.herokuapp.com/
 
