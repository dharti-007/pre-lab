<!DOCTYPE html>
<html>
<head>
<title>GitHub Demo</title>
</head>

<body>

<h1>GitHub Repository Demo</h1>
<p>This file is uploaded to a GitHub repository.</p>

<button onclick="showMsg()">Click Me</button>
<p id="msg"></p>

<script>
function showMsg(){
document.getElementById("msg").innerHTML="File updated! Commit changes to create a new version.";
}
</script>

</body>
</html>
