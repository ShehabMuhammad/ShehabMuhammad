<html>
<head>
<style> 
body {
color: #f1f1f1 ;
background-color: #333;
}
</style>
</head>
<body>

<h1 id="h">   </h1>

<script>
document.querySelector("#h").innerHTML = ("Good " + ((new Date()).getHours() < 12 ? "Morning":"Evening")) + ".";

</script>
</body>
</html>
