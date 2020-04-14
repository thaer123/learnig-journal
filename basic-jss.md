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

 (Links to an external site.)' +greeting + ' </ h3>');
