<!DOCTYPE html>
<html>
<head>
<title>introduction to js</title>
<!--<link href="" type = "" rel="">-->
<!--<script src="js/intro.js"></srcipt>-->
<style>
 .body{background-color:#34495E;
 }
 div{
   margin:auto;
   border:2px solid red;
 }
 .qcc{background-color:goldenrod;
      text-align:center;
      width:90%;
      height:10em;
      color:white;
    }
  .et{
    background-color:blue;
    width:80%;
    height:3em;
    padding:2em;
  }
 
  
  }
</style>


</head>
<body class = "body" align="auto">
  <div class ="qcc">
    <h1>Astral 7th Software</h1>
    <div class ="et">HardWork will always Pay
      <h2>Solving with Software | Defending Critical networks</h2>
    </div>
   
</body>
</html>

<!--Javescript starts here-->

<script>
  var today = new Date();
  var hourNow = today.getHours();
  var greetings;

  if (hourNow >18)
      {greetings ='Good evening!';}
  else if (hourNow >12)
      {greetings ='Good afternoon!';}
  else if(hourNow > 0)
      {greeting ='Good morning!';}
  else
      {greeting ='welcome!';}

  document.write('<h2>' + greeting + '<h2>')
</script>

