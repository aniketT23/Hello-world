# Hello-world
Beginning of the  industry 
<!DOCTYPE html>
<html>
<head>
	<title>rg</title>
</head>
<body>
<form name="abc">
	<p> Name: </p>
	<input type="text" name="Name" placeholder="enter your name">
	<p> Email: </p>
 	<input type=" 
	text" name="Email">
	<p> Address: </p>
	<input type="texr" name="Address">
	<p>SELECT YOUR COURSE    
        <select type="text" value="" name="Subject"> 
            <option>BTECH</option> 
            <option>BBA</option> 
            <option>BCA</option> 
            <option>B.COM</option> 
        </select></p>
	<button onclick="w()"> submitt</button>
	<script type="text/javascript">
		function w()
		{
			var x= document.forms["abc"]["Name"];
			var y = document.forms["abc"]["Email"];
			var z= document.forms["abc"]["Address"];
			var e= document.forms["abc"]["Subject"];
			if(x.value=="")
			{
				window.alert("please enter your name")
				return false;
			}
			if(y.value =="")
			{
				window.alert("enter your email")
				return false;
			}
			if(y.value.indexOf("@", 0) < 0)
			{
				window.alert("invalid email id")		
				return false;
			}
			if(z.value=="")
			{
				window.alert("please enter your Address")
				return false;
			}
			if(e.value=="")
			{
				
			}



		}
	</script></form>
</body>
</html>
