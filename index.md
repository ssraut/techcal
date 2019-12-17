<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="Logstylecopy.css"> 
</head>
<body>

<h2>Login form - To register click <a href="registercopy.html">here</a></h2>

<form action="/action_page.php" method="post">
  <div class="imgcontainer">
      </div>

  <div class="container">
    <label for="uname"><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>
        
    <button type="submit">Login</button>
    <label>
      <input type="checkbox" checked="checked" name="remember"> Remember me
    </label>
  </div>

  <div class="container" style="background-color:lightgreen>
    <span class="psw">Forgot <a href="passfor.html">password?</a></span>
  </div>
</form>

</body>
</html>

