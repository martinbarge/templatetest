<style>
* {
  box-sizing: border-box;
}


/* Float 4 columns side by side. */

.column {
  float: left;
  width: 25%; 
  padding: 0 10px;
}

/* Remove extra left and right margins, due to padding */

.row {margin: 0 -5px;}

/* Clear floats after the columns */

.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive columns */

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}

/* Style the counter cards */

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  background-color:#174a7d; 
  color:lightgray;
}
</style>

<h2>Simple navigation boxes grid</h2>
<p>In this example, I've set 4 columns, in which the boxes appear. The boxes are clickable and will take the user to other pages, depending on the URL you set in the boxes. You can see the a href code included below.</p>
<p>The H5P images are optional and can be removed or replaced with your own.</p>
<p>Resize the browser window to see the effect.</p>

<div class="row">
  <div class="column">
    <a href="audio.html">
     <div class="card">
      <h3>Audio Exercise</h3>
      <img src="images/h5p-logo.png" style="width:70%; margin-left:15%; margin-right:15%;">
      <p>Some optional text</p>
       </div>
    </a>
 </div>

 <div class="column">
    <a href="games.html">
    <div class="card">
      <h3>Games</h3>
      <img src="images/h5p-logo.png" style="width:70%; margin-left:15%; margin-right:15%;">
      <p>Some optional text</p>
       </div>
    </a>
 </div>
  
   <div class="column">
    <a href="maps.html">
     <div class="card">
      <h3>Maps</h3>
      <img src="images/h5p-logo.png" style="width:70%; margin-left:15%; margin-right:15%;">      
      <p>Some optional text</p>
      </div>
    </a>
 </div>
  
   <div class="column">
    <a href="js-random.html">
     <div class="card">
      <h3>Random sentences</h3>
     <img src="images/h5p-logo.png" style="width:70%; margin-left:15%; margin-right:15%;">
      <p>Some optional text</p>
       </div>
    </a>
 </div>
 
</div>

<hr>
<p>Some additional paragraph text in here.</p>
