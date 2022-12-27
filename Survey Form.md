<!DOCTYPE html>
<html lang="en">
  <link rel="stylesheet" href="styles.css">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale:1.0"> 
  <h1 id="title">freeCodeCamp Survey Form</h1></head>
  <hr>
  <body>
  <p id="description">Thank you for taking the time to help us improve the platform</p><hr>
  <form id="survey-form" >
    <div class="form-group">
    <label id="name-label">Enter your name:</label>
    <input id="name" type="text" placeholder="Abhi" required ></div>
    <div class="form-group">
   <label id="email-label">Enter your E-mail Id:</label>
    <input id="email" type="email" required placeholder="abc@gmail.com"></div>
    <div class="form-group">
     <label id="number-label">Enter your phone number: </label>
    <input id="number" type="number" min="10" max="11" required placeholder="7090123445"></div>
    <div class="form-group">
    <label for="number" id="number-label">Please enter your age:</label>
          <input id="number" type="number" min="7" max="100" required placeholder="Age"></div>
          <hr>
        <div class="form-group">
      <p>Which option best describes your current role?</p>
      <select id="dropdown" name="role" class="form-control" required>
        <option disabled selected value>Select current role</option>
        <option value="student">Student</option>
        <option value="job">Full Time Job</option>
        <option value="learner">Full Time Learner</option>
        <option value="preferNo">Prefer not to say</option>
        <option value="other">Other</option>
      </select>
    </div>
    <hr>
    <div class="form-group">
      <p>Would you recommend freeCodeCamp to a friend?</p>
      <div><label>
        <input type="radio" name="user-recommend" value="Definitely">
        Definitely</label></div>
        <div><label>
          <input type="radio" name="user-recommend" value="Maybe">
          Maybe</label></div>
          <div><label>
            <input type="radio" name="user-recommend" value="Not Sure">
            Not Sure</label></div>
            <hr>
            <div class="form-group">
              <p>What is your favorite feature of freeCodeCamp?</p>
              <select id="dropdown" name="role" class="form-control" required>
        <option disabled selected value>Select an option</option>
        <option value="Challenges">Challenges</option>
        <option value="Projects">Projects</option>
        <option value="Community">Community</option>
        <option value="Open Source">Open Source</option>
</select>
</div>
<hr>
<div class="form-group">
  <p>What would you like to see improved?<span class="clues">(Check all that apply)</span></p>
  <div><label>
    <input type="checkbox" class="input-checkbox" value="Front-end Projects">Front-end Projects</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Back-end Projects">Back-end Projects</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Data Visualization">Data Visualization</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Challenges">Challenges</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Open Source Community">Open Source Community</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Gitter help rooms">Gitter help rooms</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Videos">Videos</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="City Meetups">City Meetups</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Wiki">Wiki</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Forum">Forum</label></div>
    <div><label><input type="checkbox" class="input-checkbox" value="Additional Courses">Additional Courses</label>
    </div>
    <hr>
    <div class="form-group">
      <p>Any comments or suggestions?</p>
      <textarea
        id="comments"
        class="input-textarea"
        name="comment"
        placeholder="Enter your comment here..."
      ></textarea>
    </div>
    <hr>
    <div class="form-group">
      <center><button id="submit" type="submit" class="submit-button">Submit</button></center>
      </div>
      </body>
</html>


//---------------------------------------------------------------------------------------------------------------------------------------
CSS
body{
  background-color:pink;
}
h1{
  text-align:Center;
}
p{
  text-align:Center;
  font-size:30px;
  font-family: sans-serif;
  text-decoration:underline;
  
}
fieldset {
  border: none;
  padding: 2rem 0;
  border-bottom: 3px solid #3b3b4f;
}
input, textarea {
  background-color: #ffffff;
  border: 1px solid #0a0a23;
  color: #ffffff;}
  input[type="submit"] {
  display: block;
  width: 60%;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #3b3b4f;
  border-color: white;
  min-width: 300px;
}
input[type="file"] {
  padding: 1px 2px;
}
 textarea {
  background-color: #0a0a23;
  border: 1px solid #0a0a23;
  color: #ffffff;
 }
