# FriendFinderr
### Introduction 

Friend-Finder app makes life eay to find friend in new city with whom the thought process and personality alignes. 

* 10 Personality questions allow each user to introduce themself and app will find frience aligning to the personality match 
* Each answer are on a scale of 1 to 5 based on how much the user agrees or disagrees with a question.

### Tools use in this app 
* `server.js` file with basic npm packages of `express` and `path`
* `htmlRoutes.js` file include two routes:
   * A GET Route to `/survey` which display the survey page.
   * A default, catch-all route that leads to `home.html` which displays the home page.

* `apiRoutes.js` file contain two routes:
   * A GET route with the url `/api/friends`, to display a JSON of all possible friends.
   * A POST routes `/api/friends`, used to handle incoming survey results. This route also handle the compatibility logic.