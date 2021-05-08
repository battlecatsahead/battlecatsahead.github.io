<!DOCTYPE html>
<html>
	<head>
		<title>website 2</title>
	</head>
	<body>
	<center><h1>hello</h1></center>
	<h2>what is your favorite color?</h2>
	<input type="button" value="blue" id="buttonblue" onclick="myFunctionblue()">
		<script>
function myFunctionblue()
{   
document.body.style.backgroundColor= "blue";
}
</script><p></p>
	<input type="button" value="red" id="buttonred" onclick="myFunctionred()">
		<script>
function myFunctionred()
{   
document.body.style.backgroundColor= "red";
}
</script><p></p>
	<input type="button" value="green" id="buttongreen" onclick="myFunctiongreen()">
		<script>
function myFunctiongreen()
{   
document.body.style.backgroundColor= "green";
}
</script>

	</body>
</html>
body {
	
}
#buttonblue {
    width: 50px;
    height: 30px;
    border-radius: 10px 40px;
    box-shadow: 5px 5px;
}

#buttonred {
    width: 50px;
    height: 30px;
    border-radius: 10px 40px;
    box-shadow: 5px 5px;
}
#buttongreen {
    width: 50px;
    height: 30px;
    border-radius: 10px 40px;
    box-shadow: 5px 5px;
}
