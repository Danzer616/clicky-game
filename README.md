<h1>The Clickster<h1>

<h2>Overview</h2>
<ul>
  <li>The Clickster is a web game application where users click images of Blade Runner characters in order to earn points.  You win the game whenever you have clicked all 9 of the characters  The only catch is that the charcters move in their location with every click... </li>
  
</ul>

<h2>Technologies Used:</h2>
<ul>
  <li>React.js- UI</li>
  <li>Bootstrap- CSS framework</li>
</ul>

<h2>About the Code</h2>
<h4>Getting Started</h4>
<p>First thing I did was create the React Client-side boilerplate by typing create-react-app Clicky-game in the command line.  Next, I changed into that directory by typing 'cd Clicky-game' in the terminal. After that I typed yarn start to open the app in the browser.</p>
<h4>Starting to Code</h4>
<p>Create-react-app gives you a public folder with a basic index.html page, some basic css for the react template, an App.js file, index.js file, and some other boilerplate files.  I only had to alter two things in the index.html page: the title of my app and include a Bootstrap CDN link. I either altered or completely changed the rest of the files, adding my own style.  The bulk of the code for this app was done in the src/components directory.  I decided to make three total components for my app, however, it could have been made with much more or probably less.</p>
<h4>Components</h4>
<ul>
  <li>Card
      <p>The card component is where the character images are displayed.</p>
  </li>
  <li>Score
    <p>The score component is where the score is displayed.</p>
  </li>
  <li>Wrapper
    <p>The Wrapper component wraps the card component.</p>
  </li>
</ul>
<p>I chose not to do a separate header component but it could be done.  In fact, you could have the header component include some of the score details.</p>

<h2>The clickster can be found on Heroku <a href=''>here</a></h2>


<footer>The Clicking Game Designer and Programmer: Daniel Alexander with help from U of U Bootcamp and his friends.</footer>