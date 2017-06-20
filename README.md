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
 
 
