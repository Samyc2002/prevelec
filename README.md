<h1>Prevelec</h1>
This website aims to reduce the amount of electricity used by people in their daily lives 
by providing them a report on their usage and providing bonusses on consuming lesser energy.

<h2> Instructions for execution of the code </h2>

<h3>Software to be installed beforehand: </h3>
<ol><li> NodeJs </li></ol>

<h3>Steps to be performed: </h3>
<ol>
    <li> Go to <a href="https://account.mongodb.com/account/login?signedOut=true">MongoDB Atlas</a> and log in. Then, create a cluster and connect it. An url will be provided by MongoDB. Save it somewhere as we will need it shortly.</li>
    <li>Create a .env file in the project directory and name it ".env". Paste the following code in it.<pre>
    DB_URL='XXXXXXXXXX'
    JWT_SECRET='secret'
</pre></li>
    <li>Replace the XXXXXXXXXX in DB_URL with the link obtained in step 1. Now, follow the below steps to run it.</li>
</ol>


<h3>Running the application: </h3>
The website server is initiated by - <br>
npm i<br>
node app.js<br>
~command on git bash.<br>
<h2>About the website</h2>
<ul>
<li>You are first asked to log in to your account.
</li>
<li>
If you don't have an account, click on register and make one. Otherwise, log in with your credentials (Username is your email id).
</li>
<li>
Once logged in, you are navigated to the dashboard. The dashboard contains a graph of the energy used by the user in the year (sampled on a monthly basis).
</li>
<li>
The dashboard also contains a leaderboard of registered users and their energy consumption. 
</li>
<li>
Blog: The blog is for sharing posts and can be accessed through the navbar on the top. Posts may be composed using the compose link in navbar.
</li>
<li>
Home: An introductory page that contains information about the website.
</li>
<li>
Achievements: Lists the badges obtained by the user by fulfilling the energy conservation criterias.
</li>
<li>
Signout: Signs a user out of the active session.
</li>
</ul>

<h3>Note</h3>
<p> The website is currently incomplete and has a lot of oppurtuinities for contribution and you may use this project to get started with open source contributions as such.</p>
<p> The issues listed below are provided along with their difficulty levels so you may pick them accordingly.</p>

<h3> How to contribute </h3>
<ul>
<li> Create an Issue and wait for being assigned to it. (I shall be assigning them about twice a day) </li>
<li> Fork the repository. </li>
<li> Make changes and commits on the forked repository </li>
<li> Create a pull request to the master branch of the original repository </li>
<li> Valid pull requests will be merged</li>
</ul>

<h3> Enhancements available to do </h3> (difficulty mentioned out of 5 and graded relatively)
<ul>
<li> Fixing routes based errors (3) </li>
<li> Fixing the deprecation warning of body parser at app.js(3)</li>
<li> Making the webpage responsive (one page per PR)</li>(2)
<li> Adding database connectivity and looking in the database for valid credentials while logging in </li> (5)
<li> Typos fixing and content enhancements </li> (2)
<li> Enhancing the home page, making it the landing page </li> (4)
    <li> Enhance UI of login screen</li>
    <li> For any other enhancements, open the issue and I shall assign it if it is appropriate.</li>

<p> PS: For the issues that I have opened already, comment in the issue to let me know if you are taking it up. (like by commenting 'I would like to take this up')</p>
<p> For any queries, contact me at 190020009@iitdh.ac.in </p>
-------------------------------------------------------------------------------
