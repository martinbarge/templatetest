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

<h2>Responsive Column Cards</h2>
<p>In this example, I've set 4 columns, in which the boxes appear.</p>
<p>Resize the browser window to see the effect.</p>

<div class="row">
  <div class="column">
    <a href="www.google.com">
     <div class="card">
      <h3>Activity A</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/H5P_Logo.svg" style="width:100%;">
      <p>Some optional text</p>
       </div>
    </a>
 </div>

 <div class="column">
    <a href="www.google.com">
     <div class="card">
      <h3>Activity B</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/H5P_Logo.svg" style="width:100%;">
      <p>Some optional text</p>
       </div>
    </a>
 </div>
  
   <div class="column">
    <a href="www.google.com">
     <div class="card">
      <h3>Activity C</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/H5P_Logo.svg" style="width:100%;">
      <p>Some optional text</p>
       </div>
    </a>
 </div>
  
   <div class="column">
    <a href="www.google.com">
     <div class="card">
      <h3>Activity D</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/H5P_Logo.svg" style="width:100%;">
      <p>Some optional text</p>
       </div>
    </a>
 </div>
 
</div>
