# find_friend_final_version


 survey  have 10 questions . Each answer is on a scale of 1 to 5 based on how much the user agrees or disagrees with a question.

 server.js file should require the basic npm packages we've used in class: express and path.

 htmlRoutes.js file  include two routes:

A GET Route to /survey which should display the survey page.
A default, catch-all route that leads to home.html which displays the home page.

 apiRoutes.js file contain two routes:

A GET route with the url /api/friends. This will be used to display a JSON of all possible friends.
A POST routes /api/friends. This will be used to handle incoming survey results. This route will also be used to handle the compatibility logic.

 application's data saved inside of app/data/friends.js as an array of objects.