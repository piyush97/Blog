---
title: BootStrap Snippets
date: 2018-03-12 00:06:52
---

# Mastering Bootstrap

Ever though how to make a quick front-end for your webpage?
Well the search is over. Here are some of the quick Snippets to copy and pass it on!
All Open Source!
If you like it! Just give a star on my repo!"https://github.com/piyush97/Bootstrap-Snippets"
# Quick SignUp Form

![](https://github.com/piyush97/Bootstrap-Snippets/blob/master/img/1.jpg)

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

--------


# Contact Form in modal

![](https://github.com/piyush97/Bootstrap-Snippets/blob/master/img/2.jpg)

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


---

<a href="https://github.com/piyush97/Bootstrap-Snippets" class="pa3 tc ba br2 db">Get it on GitHub &hearts;</a>

---

## The end

Like it? [Tell me](http://github.com/piyush97).<br/>
Problem? [Use GitHub Issues](https://github.com/piyush97/Bootstrap-Snippets).
