<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>这是陈国东的网页</title> 
<script>
function displayDate(){
	document.getElementById("demo").innerHTML=Date();
}
</script>
</head>
<body>

<h1>简单的 JavaScript 程序</h1>
<p id="demo">你好，看看现在几点了？</p>

<button type="button" onclick="displayDate()">显示日期</button>

</body>
</html>
