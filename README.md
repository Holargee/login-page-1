<!DOCTYPE html>
<html lang="en">
<head>
				<meta charset="UTF-8">
				<meta name="viewport"content="width=device-width,initial-scale=1.0">
	<link rel="stylesheet" href="clogin page.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<style>
					body{
				background-color:rgb(100,100,100);
}
form{
				background-color:rgb(225,225,225);
				margin-top:30%;
				width:200px;
				height:250px;
	justify-content:center;
	       margin-left:15%;    
	       padding:20px;   
				box-shadow:20px 20px 10px grey;
}
.fill{
				border-left:none;
				border-top:none;
				border-right:none;
				height:30px;
				width:180px;
				background-color:transparent;
				padding-left:20px;
				font-size:15px;
				font-family:monospace;
				border-color:grey;
}
#circle{
				margin-left:35%;
				font-size:50px;
			 float:center;
}
#eye{
				position:absolute;
				margin-left:170px;
				margin-top:-30px;
				font-size:25px;
}
.btn{
	     margin-left:0%;
	     color:white;
	     font-family:sans-serif;
	     font-size:17px;
	     padding:3px;
	     width:200px;
	     background-color:rgb(0,0,200);
}
.btn:active{
				background-color:rgb(0,0,50)
}
.forget{
				font-size:14px;
				margin-left:2px;
}
.wel{
				margin-top:-60px;
				margin-left:28%;
				font-size:40px;
				font-family:cursive;
				position:absolute;
}
a:visited{
				color:blue;
}

	</style>
	<script type="text/javascript">
				function validate(){
	var a = document.getElementById("username").value;
	var b = document.getElementById("password").value;						if(a=="user" && b=="pass")
	{alert("welcome");location.href="/storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/side gig.ng/side gig.html";}
else	if(a=="hi" && b=="hey")
	{alert("welcome");location.href="/storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/side gig.ng/side gig.html";}
	else if(a!=="user"){alert("wrong username");}
	else{alert("wrong password");}
				}
function my(){
	 				var a = document.getElementById("password");
	 				if(a.type==="password")
	 				{a.type="text";}
	 	else{a.type="password"};
	 }
	 function me(){
 var a = document.getElementById("eye");
 if(a.className==="fa fa-eye-slash")
    {a.className="fa fa-eye";}
else{a.className="fa fa-eye-slash";}
	 	}
	</script>
				<title>login page</title>
</head>
<body>
				<div class="wel">Welcome</div>
				<form>
								<i id="circle"class="fa fa-user-circle"></i>
								<br><br>
			<input type="text"id="username"class="fill"placeholder="enter username"required>
			<br><br>
			<input type="password"class="fill"id="password"placeholder="enter password"required>
			<i onclick="my();me()"id="eye"class="fa fa-eye-slash"></i>
<span class="forget">forgot password?	<a href="#">click here</a></span><br><br>
<input type="button"class="btn" value="log in"			onclick="validate()">
not a member? <a href="#">register.</a>
			</form>
</body>
</html>

