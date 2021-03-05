<!DOCTYPE html> 
<html lang="en">
<head> 
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
*{
box-sizing: border box;
}
/* Create two equal columns that floats next to each other */
.column 
{
float: left; 
width: 50%; 
padding: 10px; 
height: 300px; 
/* Should be removed. Only for demonstration */}
/* Clear floats after the columns */
.row:
after 
{
content: "";
display: 
table; 
clear: 
both; 
}
</style>
</head>
<body>

<h2>Two Equal Columns</h2>

<div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p> In the column 1 we have number of Students Boys </p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p> In the column 2 we have number of Students Girls</p>
  </div>
</div>

</body>
</html>

<hr>
<hr>


<h2>Lab6.html</h2>
<h2> Hie Y. Simon</h2>





