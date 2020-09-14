# c02
var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
}else if (hourNow > 12) {
greeting = ' Good afternoon!';
}else if (hourNow > 0) {
greeting = 'Good morni ng!';
}else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3> ');


<!DOCTYPE html>
<html>
<head>
<title>Constructive &amp; Co.</ title>
<link rel ="stylesheet" href="css/ cOl.css" />
</ head>
<body>
<hl>Constructive &amp ; Co. </ hl>
<script src="js/ add-content.js"></ script>
<p>For all orders and i nquiries please cal l
<em>SSS-3344</ em></ p>
</ body>
</html> 
