DATA TYPES
JavaScript distinguishes between numbers,
strings, and true or false values known as
Booleans.
NUMERIC DATA TYPE
The numeric data type handles
numbers.
0.75
For tasks that involve counting
or calculating sums, you will
use numbers 0-9. For example,
five thousand, two hundred and
seventy-two would be written
5272 (note there is no comma
between the thousands and
the hundreds). You can also
have negative numbers (such
as -23678) and decimals (three
quarters is written as 0.75).
Numbers are not only used for
things like calculators; they
are also used for tasks such
as determining the size of the
screen, moving the position of
an element on a page, or setting
the amount of time an element
should take to fade in.
@ BASIC JAVASCRIPT INSTRUCTIONS
STRING DATA TYPE
The strings data type consists of
letters and other characters.
'H.
1 ' Ivy! 1
Note how the string data type is
enclosed within a pair of quotes.
These can be single or double
quotes, but the opening quote
must match the closing quote.
Strings can be used when
working with any kind of text.
They are frequently used to add
new content into a page and they
can contain HTML markup.
BOOLEAN DATA TYPE
Boolean data types can have one
of two values: true or false.
true
It might seem a little abstract at
first, but the Boolean data type is
actually very helpful.
You can think of it a little like a
light switch - it is either on or off.
As you will see in Chapter 4,
Booleans are helpful when
determining which part of a
script should run.
In addition to these three data types, JavaScript also has others (arrays,
objects, undefined, and null) that you will meet in later chapters.
Unlike some other programming languages, when declaring a variable in
JavaScript, you do not need to specify what type of data it will hold. 
USING A VARIABLE TO
STORE A NUMBER
JAVASCRIPT
var price;
var quantity;
var total;
price = 5;
quantity = 14;
total = price * quantity;
c02/j s/numeri c-vari ab 1 e .j s
var el = document.getElementByid( ' cost ');
el .textContent = '$' +total;
W:ii.§11
<hl>Elderflower</hl>
<div id="content">
<h2>Custom Signage</h2>
c02/numeric-vari able .html
<div id="cost ">Cost: $5 per tile</ div>
<img src="images/preview.jpg" alt="Sign" />
</div>
<scri pt src="js/numeric-variable .js"></script>
CUSTOM SIGNAGE::
Preview: m T AIG u E H olu s E
Here, three variables are created
and values are assigned to them.
• price holds the price of an
individual tile
• quantity holds the number
of tiles a customer wants
• to ta 1 holds the total cost of
the tiles
Note that the numbers are not
written inside quotation marks.
Once a value has been assigned
to a variable, you can use the
variable name to represent that
value (much like you might have
done in algebra). Here, the total
cost is calculated by multiplying
the price of a single tile by the
number of tiles the customer
wants.
The result is then written into
the page on the final two lines.
You see this technique in more
detail on p194 and p216.
The first of these two lines finds
the element whose id attribute
has a value of cost, and the final
line replaces the content of that
element with new content.
Note: There are many ways to
write content into a page, and
several places you can place
your script. The advantages and
disadvantages of each technique
are discussed on p226. This
technique will not work in IE8. 
