<!DOCTYPE html>
<!-- This file, "test.html", is at the root of the Document Object Model -->
<html>
<head>.
  
<title>Multifile JavaScript Test</title>
    
<!-- "demostyle.css" is an external style sheet -->
<link id = "css" rel="stylesheet" type="text/css" href="demostyle.css">
    
<!-- "demo.js" is an external script -->
<script src="demo.js"></script>
    
</head>

<body>
<h1>Multiple File Demo</h1>
<p id="msg">Message for you ...</p>

<form name="theForm">
<input type="text"></input>
<input type="button" value="Change Message" onclick="changeMsg()">
</form>

</body>
</html>
