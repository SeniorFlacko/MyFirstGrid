# MyFirstGrid
My first Grid Made In Bootstrap 3
We use:
-Bootstrap 3.3.7
<br>
-JQuery 3.2.1
<br>
-Our own styles.css 
<br>
Our tree is :

header > container
<br><br>
container > <br>
  -section(Row)><br>
    -article [col 9]<br>
    -aside [col 3]
  <br><br>
  -div (Row)> <br> 
    -div [col 3]<br>
    -div [col 3]<br>
    -div [col 3]<br>
    -div [col 3]<br>
    
footer > container

We manipulate size of columns to differents size screen by adding a class="col-xs-12 col-sm-4 col-md-3"
and saying how we want values displayed for extra small(mobile), small(tablet),medium(tablet), 
and large by default taking last col value in this case md-3 so col-lg-3 :smiley:

<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_099_zpsqfwxbu5l.png">

<h2>text html</h2>
	to text..
<pre>
text-center|justify|left|right
text-muted|primary|info|succes|warning|danger
text-lowecase|uppercase|capitalize
to text background color:
bg-primary|info|succes|warning|danger
to remark text
b
strong
mark
u
code
pre
small
blockquote

Shorcut with Emmet:
Making a row with three columns with size 4 and each column has 6 child paragraphs
div.row>div.col-md-4*3>p*6
</pre>
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_100_zpsfddqezy7.png">

<h2>Making forms in Bootstrap</h2>
<h4>Form 1:Normal Form</h4>
This is my first form made in bootstrap :

For forms we have an special class: <strong>form-control</strong>
wich is applied to inputs of type:
<ul>
<li>text</li>
<li>password</li>
<li>datetime</li>
<li>month</li>
<li>week</li>
<li>email</li>
<li>url</li>
<li>search</li>
<li>tel</li>
<li>color</li>
</ul>

We have another special class <strong>form-group</strong>
To make groups formed generally by [label,input] tags this serves to group tags
and make a seperation beetween different fields of the form
Our first form look like:
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_106_zpssaga8wth.png">

<h4>Form 2:Inline Form</h4>
this is my first inline form
We add a class to form tag 
<br>
<strong>form-inline</strong> 
<br>
this will make our form inline and in past we have form-group class now we use 
<br><strong>input-group</strong><br>
to stick by using 
<br>
<strong>input-group-addon</strong> 
<br>
an @ to a email field so our second form would like this.

<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_107_zpshfpfnrs2.png">

<h4>Form 3:Horizontal Form</h4>
This is about making our custom responsive form by giving size of columns to the labels and inputs
so we can customize how fields would look when is a mobile or a tablet or a desktop
we make this possible by adding a class to labels called <pre>class="control-label col-md-10"</pre> and wrapping in a div
our inputs and making that div to have a class calle <pre>div class="col-md-10"</pre> with our customize size just like we did in our grids... so our form-horizontal would look like this:
<h6>Important note: to wrap a tag in a div we use Emmet shorcut:</h6>
<pre>Ctrl + Shift+ g</pre>
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_108_zpsmudaxvgb.png">

The most important or relevants classes in forms are:

<pre>
form-inline
form-horizontal
form-group
form-control
input-group
input-group-addon
control-label col-md-10
</pre>

<h2>My first Buttons on Bootsrap</h2>
There are 7 types of buttons:default,info,primary,succes,warning,danger,link
<br>
With 4 different sizes :xsm (Extra Small), sm(Small),md(medium),lg(Large) 
<br>

Some interesting classes are:
<ul>
<li>btn-block [ocupa todo el espacio de la columna donde este]</li>
<li>active [agrega el tan famoso efecto active a los botones]</li>
<li>disabled [agrega el efecto que inhabilita el boton]</li>
</ul>
We can implement a button in 3 different ways<br>
	-Button Tag<br>
	-Anchor Tag<br>
	-Input Type=Button<br>

Our buttons are beautiful: :smiley:
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_109_zpsugu1w3dn.png">


<h2>First Images on bootstrap</h2>
For images we have 4 important classes
<ul>
	<li>img-responsive</li>
	<li>img-rounded</li>
	<li>img-circle</li>
	<li>img-thumbnail</li>
</ul>

Our sample of RESPONSIVE images:
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_103_zpss3wcrppv.png">

<h2>Responsive Utilities</h2>
<h5>Classes for hide and show a div or an element</h5>
<ul>
	<li>visible-lg [hace el contenido visible solo en extra pequeño]</li>
	<li>visible-md  [hace el contenido visible solo en extra pequeño]</li>
	<li>hidden-sm [contenido oculto para dispositivo pequeño]</li>
	<li>hidden-xs [contenido oculto para dispositivo extra pequeños]</li>
</ul>
<h2>By default our contents are show on Block so</h2>
<ul>
	<li>-visible-md-inline  [for making inline]</li>
	<li>-visible-md-block   [spec that will be block]</li>
</ul>
 if we make <pre>aside class="visible-lg visible-md col-xs-12 col-sm-4 col-md-3"</pre>
 We can only see sidebar in lg and md sizes 
 like this:
 <img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_099_zpsqfwxbu5l.png">
 but if the screen is sm (small) or xsm(Extra small)
 it will not be display aside it will just disappear like this
 <img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_111_zpsqpgrkd9d.png">
 <img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_112_zps7dveffum.png">
 
 
<h2>Using ICONS on Bootstrap</h2>
We can use icons in different components like a button,paragraph,headers etc.
--->For using an icon we need to make an span element inside the tag we want
and the span need to have a class with the name of that icon:

<pre>span class="glyphicon glyphicon-asterisk"</pre>
<strong>span</strong> is a child of an header tag in the next example:

<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_115_zpsfpceppff.png">


<h2>Dropdown Buttons</h2>

Making dropdown button is interesting because it will use javascript fucntionality behind the scenes
	<ul>
		<li>for making a dropdown menu we need:</li>
		<li>1.- Wrap a trigger[button] and a list menu in a div with .dropdown</li>
		<li>2.- To say that a button is a dropdown button we add .dropdown-toggle</li>
		<li>3.- To say a menu is a dropdown-menu we add .dropdown-menu</li>
		<li>4.- To link button + menu we add an id to a button then in menu we point to that id</li>
	</ul>
We use a special icon called caret, in our menu we can have:
.dropdown-header wich is a header and also a .divider wich is a divider and 
also we can add .disabled class to an element li of our ul a.k.a menu

<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccioacuten_116_zpsggckstyt.png">
 
 <h2>Input Groups</h2>
 We have already make an input-group in forms but this are some other examples about it:
So we say:

	An addon is like an icon:
	We need a span implementing input-group-addon or input-group-btn
	but first
	For making input-groups we need: 
	form-group
	and as a child 
	input-group
	so we can stick a caracter to an input
	in resume

	.form-group : .input-group : span.input-group-addon

	
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccioacuten_117_zpsz0ca6wx2.png">

<h2>Nav Tab and Nav Pills</h2>

First of all for making our first navbar we need to know what are nav tabs and nav pills:
so:

For desmystifying nav tabs and nav pills we need to say that are just unordered list a.k.a <strong>ul</strong>
implementing class="nav nav-tab" or class="nav nav-pills" respectively

But we can make those navs stacked, or justified, and also they can have a dropdown.
<h6>Nav tabs and Nav Pills are just simplified versions of Navbars</h6>
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_118_zpsqxsnh06y.png">
	
<h2>Navbar!!!!!!!!!!!!</h2>
<h6>This is like the most beautiful part of bootstrap c:</h6>


	Essential idea about navabars is that a navbar is a unordered list
	so
	Make an ul with anchors as li
	Add to ul the class .nav navbar-nav
	Wrap that ul in a nav with class navbar navbar-default
	make a div with class navbar-header
	inside of div.navbar-header put toggle button and brand name
	Wrap ul in a .collapse navbar-collapse and add id="{id on toggle button}"

	and..
	if you need a form you need to tell that will be inline so wrap that form in .navbar-form
	if you need a button put .navbar-btn
	if you need text put .navbar-text

	If you need aligments put navbar-left or .navbar-right in a separate ul

	You can use .navbar-fixed-top or navbar-static-top,
	but first make content of the nav inside a container or container-fluid

	:D
And our navbar would look like this:
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_121_zpsgbyhih97.png">

<h2>Breadcrumbs</h2>
<h4>It is curious that in breadcrumbs we put ordered list [ol] instead unordered list {ul}</h4>
And breadcrums are just ordered list with .breadcrumb :smiley:
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_122_zpswjbr15z2.png">


<h2>Pagination</h2>
<h6>Guess What, Pagination are just ul with .pagination with different sizes</h6>
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_123_zpswxpbsigy.png">

<h2>Labels</h2>
If we need some kind of flag to our elements we have <strong>label</strong> tag
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccin_124_zpsdrujnpne.png"> 


<h2>Badges</h2>
For notifications features we have badges
<h6>it is like an icon or a label we put a span </h6>
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccioacuten_125_zps7tzndneq.png"> 

<h2>Jumbotron</h2>
<h5>Jumbotron is Like a giant box</h5>
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccioacuten_126_zpslfycc1c7.png">

<h2>An iteresting class .page-header to use with headers</h2>
<h6>It kinds remember me my first CV Thats why I love it!! :D</h6>
<img src="http://i1093.photobucket.com/albums/i422/Psycriss__/Seleccioacuten_127_zpselvown5o.png">


