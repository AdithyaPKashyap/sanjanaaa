<html>
<body>
<script>
function validateform(){
var name=document.myform.name.value;
var password=document.myform.password.value;
if(name==null || name==")
{
alert(name can't be black");
return false;
}
else if(password.length<6)
{
alert("password must be at least 6 characters long.");
return false;
}
}
</script>
<body>
<form name="myform" method="post" action="valid.html" onsubmit="return validateform()">
name: <input type="text"name="name"><br/>
password; <input type="password"name="password"><br/>
<input type="submit"value="register">
</form>
</body>
</html>
