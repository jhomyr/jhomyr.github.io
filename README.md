
<div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
  <a href="#band" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">The Course</a>
</div>

<!-- Page content -->
<div class="w3-content" style="max-width:2000px;margin-top:46px">

   <!-- The Band Section -->
  <div class="w3-container w3-content w3-center w3-padding-64" style="max-width:800px" id="band">
    <h2 class="w3-wide">CS 1130 - Introduction to Computing</h2>
    <p class="w3-opacity"><i> <bold> by John Roy A. Geralde - Class Instructor</bold></i></p>
    <p class="w3-justify">This is the website for viewing HTML, Javascript Programming and CSS Examples for students
      who are taking the Introduction to Computing Class (CS 1130) under the Computer Studies Division, School of Arts and Sciences
      of the Ateneo de Davao University. Simple Examples involving Basic HTML, Javascript Functions, User Interaction, 
      Mathematical Calculations, Simple Styling and Page Layouts are shown.</p>
    
      <br>
      <h2>
      Student Assignments:  
      </h2>
      <br>
      <h3>Assignment #1 - Conversion (Celsius to Fahrenheit, Fahrenheit to Celsius, Meters to Feet, Feet to Meters)</h3>
      <h3>Assignment #2 - Income Tax Calculator </h3>
      <h3>Assignment #3 - Factorial (While Loop), Sum (Do While Loop) and Average (For Loop) of First N Natural Numbers</h3>
      <h3>Assignment #4 - Simple Payroll </h3>

      <br>
      <h2>*** All Assignments are Due on <strong>DECEMBER 7, 2024</strong> *** </h2>
      <h2> The Rubrics will be shown in our Daigler20 class </h2>
      <h4> Upload and launch the pages in your specified github  or w3spaces website. </h4>
     


  </div>

  
<!-- End Page Content -->
</div>

<script>
// Automatic Slideshow - change image every 4 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 4000);    
}

// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}

// When the user clicks anywhere outside of the modal, close it
var modal = document.getElementById('ticketModal');
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>

</body>
</html>
