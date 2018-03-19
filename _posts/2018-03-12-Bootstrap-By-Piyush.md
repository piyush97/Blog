---
title: BootStrap Snippets
date: 2018-03-12 00:06:52
---

# Mastering Bootstrap

Ever though how to make a quick front-end for your webpage?
Well the search is over. Here are some of the quick Snippets to copy and pass it on!
All Open Source!
If you like it! Just give a star on my repo!
"<https://github.com/piyush97/Bootstrap-Snippets>"

# Quick SignUp Form

![Some text](/gh-pages/img/1.jpg)

# Open: <a href src="https://github.com/piyush97/Bootstrap-Snippets/tree/master/Quick%20Signup%20Form">https://github.com/piyush97/Bootstrap-Snippets/tree/master/Quick%20Signup%20Form</a>
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://fonts.googleapis.com/css?family=Roboto:400,700" rel="stylesheet">
<title>Bootstrap Quick Sign up Form</title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<style type="text/css">
	body {
		color: #fff;
		background: #4c535d;
		font-family: 'Roboto', sans-serif;
	}
    .form-control {
        min-height: 41px;
		box-shadow: none;
		border-color: #e1e4e5;
	}
    .form-control:focus {
		border-color: #5fcaba;
	}
    .form-control, .btn {        
        border-radius: 3px;
    }    
	.signup-form {
		width: 400px;
		margin: 0 auto;
		padding: 30px 0;
	}
    .signup-form form {
		color: #9ba5a8;
		border-radius: 3px;
    	margin-bottom: 15px;
        background: #fff;
        box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
        padding: 30px;
    }
	.signup-form h2 {
		color: #333;
		font-weight: bold;
        margin-top: 0;
    }
    .signup-form hr {
        margin: 0 -30px 20px;
    }
	.signup-form .form-group {
		margin-bottom: 20px;
	}
    .signup-form label {
		font-weight: normal;
		font-size: 13px;
	}
    .signup-form .btn {        
        font-size: 16px;
        font-weight: bold;
		background: #5fcaba;
		border: none;
		min-width: 140px;
    }
	.signup-form .btn:hover, .signup-form .btn:focus {
		background: #3fc0ad;
        outline: none !important;
	}
	.signup-form a {
		color: #fff;
		text-decoration: underline;
	}
    .signup-form a:hover {
		text-decoration: none;
	}
	.signup-form form a {
		color: #5fcaba;
		text-decoration: none;
	}
	.signup-form form a:hover {
		text-decoration: underline;
	}
</style>
</head>
<body>
<div class="signup-form">
    <form action="/examples/actions/confirmation.php" method="post">
		<h2>Sign Up</h2>
		<p>It's free and only takes a minute.</p>
		<hr>
        <div class="form-group">
        	<input type="text" class="form-control" name="username" placeholder="Username" required="required">
        </div>
        <div class="form-group">
        	<input type="email" class="form-control" name="email" placeholder="Email Address" required="required">
        </div>
		<div class="form-group">
            <input type="password" class="form-control" name="password" placeholder="Password" required="required">
        </div>
		<div class="form-group">
            <input type="password" class="form-control" name="confirm_password" placeholder="Confirm Password" required="required">
        </div>
		<div class="form-group">
            <button type="submit" class="btn btn-primary btn-block btn-lg">Sign Up</button>
        </div>
		<p class="small text-center">By clicking the Sign Up button, you agree to our <br><a href="#">Terms &amp; Conditions</a>, and <a href="#">Privacy Policy</a>.</p>
    </form>
	<div class="text-center">Already have an account? <a href="#">Login here</a></div>
</div>
</body>
</html>                            
```

* * *

# Contact Form in modal

![Some text](/gh-pages/img/2.jpg)
 # Open: https://github.com/piyush97/Bootstrap-Snippets/tree/master/Contact%20form%20in%20modal
  
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Contact Form inside Modal</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto|Varela+Round">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style type="text/css">
    body {
      color: #566787;
      background: #f5f5f5;
      font-family: "Varela Round", sans-serif;
    }

    .form-control:focus {
      border-color: #8464ca;
      box-shadow: 0 0 8px #beace3;
    }

    .contact-modal {
      width: 600px;
      padding: 50px;
      margin: 30px auto;
    }

    .contact-modal h4 {
      font-size: 26px;
      display: inline-block;
    }

    .contact-modal .form-control,
    .contact-modal .btn {
      min-height: 38px;
      border-radius: 1px;
      outline: none;
    }

    .contact-modal .btn-primary {
      min-width: 100px;
      background: #8464ca;
      border: none;
    }

    .contact-modal .btn-primary:hover {
      background: #6d45c0;
    }

    .contact-modal .btn-primary:focus {
      box-shadow: 0 0 8px rgba(132, 100, 202, 0.6);
    }

    .contact-modal .btn-link {
      color: #6d45c0;
    }

    .contact-modal label {
      opacity: 0.9;
      font-weight: normal;
      font-size: 95%;
    }

    .contact-modal textarea {
      resize: vertical;
    }

    .contact-modal.modal-dialog {
      width: 480px;
    }

    .contact-modal .modal-header {
      padding: 20px 35px 14px;
    }

    .contact-modal .modal-content {
      border-radius: 1px;
    }

    .contact-modal .close {
      position: absolute;
      right: 35px;
      top: 25px;
    }

    .contact-modal .modal-body {
      padding: 20px 35px 35px;
    }

    .hint-text {
      opacity: 0.8;
    }

    .trigger-btn {
      display: inline-block;
      margin: 100px auto;
    }
  </style>
</head>

<body>
  <div class="text-center">
    <!-- Button HTML (to Trigger Modal) -->
    <a href="#myModal" class="trigger-btn" data-toggle="modal">Click to Open Contact Modal</a>
  </div>

  <!-- Modal HTML -->
  <div id="myModal" class="modal fade">
    <div class="modal-dialog contact-modal">
      <div class="modal-content">
        <div class="modal-header">
          <h4 class="modal-title">Contact Us</h4>
          <button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
        </div>
        <div class="modal-body">
          <form action="/examples/actions/confirmation.php" method="post">
            <div class="form-group">
              <label for="inputName">Name</label>
              <input type="text" class="form-control" id="inputName" required>
            </div>
            <div class="form-group">
              <label for="inputEmail">Email</label>
              <input type="email" class="form-control" id="inputEmail" required>
            </div>
            <div class="form-group">
              <label for="inputMessage">Message</label>
              <textarea class="form-control" id="inputMessage" rows="4" required></textarea>
            </div>
            <input type="submit" class="btn btn-primary" value="Send">
            <input type="button" class="btn btn-link" data-dismiss="modal" value="Cancel">
          </form>
        </div>
      </div>
    </div>
  </div>
</body>

</html>
```

* * *

# Yellow form Pacifico

![Some text](/gh-pages/img/3.jpg)
# Open: https://github.com/piyush97/Bootstrap-Snippets/tree/master/Form%20Yellow%20Pacifico
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Contact Form with Yellow Background</title>
  <link href="https://fonts.googleapis.com/css?family=Roboto|Courgette|Pacifico:400,700" rel="stylesheet">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style type="text/css">
    body {
      color: #000;
      background: #fcda2e;
      font-family: "Roboto", sans-serif;
    }

    .contact-form {
      padding: 50px;
      margin: 30px auto;
    }

    .contact-form h1 {
      font-size: 42px;
      font-family: 'Pacifico', sans-serif;
      margin: 0 0 50px;
      text-align: center;
    }

    .contact-form .form-group {
      margin-bottom: 20px;
    }

    .contact-form .form-control,
    .contact-form .btn {
      min-height: 38px;
      border-radius: 2px;
    }

    .contact-form .form-control {
      border-color: #e2c705;
    }

    .contact-form .form-control:focus {
      border-color: #d8b012;
      box-shadow: 0 0 8px #dcae10;
    }

    .contact-form .btn-primary {
      min-width: 250px;
      color: #fcda2e;
      background: #000;
      margin-top: 20px;
      border: none;
    }

    .contact-form .btn-primary:hover {
      color: #fff;
    }

    .contact-form .btn-primary i {
      margin-right: 5px;
    }

    .contact-form label {
      opacity: 0.9;
    }

    .contact-form textarea {
      resize: vertical;
    }

    .bs-example {
      margin: 20px;
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="row">
      <div class="col-md-8 col-md-offset-2 m-auto">
        <div class="contact-form">
          <h1>Get in Touch</h1>
          <form action="/examples/actions/confirmation.php" method="post">
            <div class="row">
              <div class="col-sm-6">
                <div class="form-group">
                  <label for="inputName">Name</label>
                  <input type="text" class="form-control" id="inputName" required>
                </div>
              </div>
              <div class="col-sm-6">
                <div class="form-group">
                  <label for="inputEmail">Email</label>
                  <input type="email" class="form-control" id="inputEmail" required>
                </div>
              </div>
            </div>
            <div class="form-group">
              <label for="inputSubject">Subject</label>
              <input type="text" class="form-control" id="inputSubject" required>
            </div>
            <div class="form-group">
              <label for="inputMessage">Message</label>
              <textarea class="form-control" id="inputMessage" rows="5" required></textarea>
            </div>
            <div class="text-center">
              <button type="submit" class="btn btn-primary"><i class="fa fa-paper-plane"></i> Send</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</body>

</html>
```

# RainBow navbar
![Some text](/gh-pages/img/4.jpg)

# Open: https://github.com/piyush97/Bootstrap-Snippets/tree/master/RainBow%20Nav
```html
<link href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/js/bootstrap.min.js"></script>
<script src="//code.jquery.com/jquery-1.11.1.min.js"></script>
<!------ Include the above in your HEAD tag ---------->

<div class="navbar-wrapper">
    <div class="container-fluid">
        <nav class="navbar navbar-fixed-top">
            <div class="container">
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="#">Logo</a>
                </div>
                <div id="navbar" class="navbar-collapse collapse">
                    <ul class="nav navbar-nav">
                        <li class="active"><a href="#" class="">Home</a></li>
                        <li class=" dropdown">
                            <a href="#" class="dropdown-toggle " data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Departments <span class="caret"></span></a>
                            <ul class="dropdown-menu">
                                <li class=" dropdown">
                                    <a href="#" class="dropdown-toggle " data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">View Departments</a>
                                </li>
                                <li><a href="#">Add New</a></li>
                            </ul>
                        </li>
                        <li><a href="#">Add New</a></li>
                        <li class=" dropdown"><a href="#" class="dropdown-toggle " data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Managers <span class="caret"></span></a>
                            <ul class="dropdown-menu">
                                <li><a href="#">View Managers</a></li>
                                <li><a href="#">Add New</a></li>
                            </ul>
                        </li>
                        <li class=" dropdown"><a href="#" class="dropdown-toggle active" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Staff <span class="caret"></span></a>
                            <ul class="dropdown-menu">
                                <li><a href="#">View Staff</a></li>
                                <li><a href="#">Add New</a></li>
                                <li><a href="#">Bulk Upload</a></li>
                            </ul>
                        </li>
                        <li class=" down"><a href="#" class="dropdown-toggle active" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">HR <span class="caret"></span></a>
                            <ul class="dropdown-menu">
                                <li><a href="#">Change Time Entry</a></li>
                                <li><a href="#">Report</a></li>
                            </ul>
                        </li>
                    </ul>
                    <ul class="nav navbar-nav pull-right">
                        <li class=" dropdown"><a href="#" class="dropdown-toggle active" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Signed in as  <span class="caret"></span></a>
                            <ul class="dropdown-menu">
                                <li><a href="#">Change Password</a></li>
                                <li><a href="#">My Profile</a></li>
                            </ul>
                        </li>
                        <li class=""><a href="#">Logout</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</div>
```

## Css file

```css
body{
    background: #8999A8;
}
.navbar, .dropdown-menu{
background:rgba(255,255,255,0.25);
border: none;

}

.nav>li>a, .dropdown-menu>li>a:focus, .dropdown-menu>li>a:hover, .dropdown-menu>li>a, .dropdown-menu>li{
  border-bottom: 3px solid transparent;
}
.nav>li>a:focus, .nav>li>a:hover,.nav .open>a, .nav .open>a:focus, .nav .open>a:hover, .dropdown-menu>li>a:focus, .dropdown-menu>li>a:hover{
  border-bottom: 3px solid transparent;
  background: none;
}
.navbar a, .dropdown-menu>li>a, .dropdown-menu>li>a:focus, .dropdown-menu>li>a:hover, .navbar-toggle{
 color: #fff;
}
.dropdown-menu{
      -webkit-box-shadow: none;
    box-shadow:none;
}

.nav li:hover:nth-child(8n+1), .nav li.active:nth-child(8n+1){
  border-bottom: #C4E17F 3px solid;
}
.nav li:hover:nth-child(8n+2), .nav li.active:nth-child(8n+2){
  border-bottom: #F7FDCA 3px solid;
}
.nav li:hover:nth-child(8n+3), .nav li.active:nth-child(8n+3){
  border-bottom: #FECF71 3px solid;
}
.nav li:hover:nth-child(8n+4), .nav li.active:nth-child(8n+4){
  border-bottom: #F0776C 3px solid;
}
.nav li:hover:nth-child(8n+5), .nav li.active:nth-child(8n+5){
  border-bottom: #DB9DBE 3px solid;
}
.nav li:hover:nth-child(8n+6), .nav li.active:nth-child(8n+6){
  border-bottom: #C49CDE 3px solid;
}
.nav li:hover:nth-child(8n+7), .nav li.active:nth-child(8n+7){
  border-bottom: #669AE1 3px solid;
}
.nav li:hover:nth-child(8n+8), .nav li.active:nth-child(8n+8){
  border-bottom: #62C2E4 3px solid;
}

.navbar-toggle .icon-bar{
    color: #fff;
    background: #fff;
}
```
