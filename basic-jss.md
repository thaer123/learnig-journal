# CREATING A BASIC JAVASCRIPT
JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day.
 (Links to an external site.)Example JS Code
var today= new Date();

var hourNow = today.getHours();

var greeting;

if (hourNow > 18) {

greeting= 'Good evening!';

else if (hourNow > 12) {

greeting = ' Good afternoon!';

else if (hourNow > 0) {

greeting = 'Good morni ng!';

else {

greeting = 'Welcome! ' ;

document .write( '



# HOW HTML, CSS& JAVASCRIPT FIT TOGETHER

Before diving into the JavaScript language, you
need to know how it will fit together with the
HTML and CSS in your web pages.
Web developers usually talk
about three languages that
are used to create web pages:
HTML, CSS, and JavaScript.
<html>
CONTENT LAYER
. html files
This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics.
Where possible, aim to keep the
three languages in separate files,
with the HTML page linking to
CSS and JavaScript files.
{css}
PRESENTATION LAYER
. css files
The CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.).
Programmers often refer to this as a separation of concerns.
8 THE ABC OF PROGRAMMING 


# LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE 

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

# CHANGING THE VALUE OF A VARIABLE 
var inStock;

var shipping;

inStock = true;

shipping = false;

JAVASCR IPT

/* Some other processing might go here and , as

a result , the script might need to change t hese

values */

inStock = false;

shipping = true;

var elStock = document.getElementByld('stock');

elStock .className = inStock;

var elShip = document .getElementByld('shipping');

elShip .className = shipping; 










