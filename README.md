Best view in Firefox with flexbox enabled. Webkit browser need to fix a bug in order to view the perfect vertical rhythm. 

Additional polyfills need to make older browsers to work.

## Features:

* Modular CSS framework
* 1.618 unitless line height
* 1 to 12 column grid powered by CSS3 flexbox
* Fibonacci sequence in h1 h2 h3 h4 h5 h6 and other helper like .h0 - .h6
* Use 1em or 16px for readable text
* Use normalize.css
* Build the font stacks using comprehensive survey (http://www.codestyle.org/css/font-family/index.shtml) 
* Responsive support for 300px, 748px, 978px, 1218px and 1378px

### Include Natural in your page

<link rel="stylesheet" href="natural.css">

### Simple flexible grid

<nav class='block'>
	<div class='unit size1of2'>
		<p class='text-centering'>1/2</p>
	</div>
	<div class='unit size1of2'>
		<p class='text-centering'>1/2</p>
	</div>
</nav>

### Simple flexible grid with container

<nav class='block'>
	<div class='container center'>
		<div class='unit size1of2'>
			<p class='text-centering'>1/2</p>
		</div>
		<div class='unit size1of2'>
			<p class='text-centering'>1/2</p>
		</div>
	</div>
</nav>

### Simple flexible grid with gutter

<nav class='block gutter'>
	<div class='container center'>
		<div class='unit size1of2'>
			<p class='text-centering'>1/2</p>
		</div>
		<div class='unit size1of2'>
			<p class='text-centering'>1/2</p>
		</div>
	</div>
</nav>

### Simple flexible grid with nesting

<nav class='block'>
	<div class='container center'>
		<div class='unit size1of2'>
			<p class='text-centering'>1/2</p>
		</div>
		<div class='unit size1of2'>
			<div class='block'>
				<div class='unit size1of2'>
					<p class='text-centering'>1/2</p>
				</div>
				<div class='unit size1of2'>
					<p class='text-centering'>1/2</p>
				</div>
			</div>
		</div>
	</div>
</nav>

### Mix block with gutter and block without gutter

<nav class='block gutter'>
	<div class='container center'>
		<div class='unit size1of2'>
			<p class='text-centering'>1/2</p>
		</div>
		<div class='unit size1of2'>
			<div class='block'>
				<div class='unit size1of2'>
					<p class='text-centering'>1/2</p>
				</div>
				<div class='unit size1of2'>
					<p class='text-centering'>1/2</p>
				</div>
			</div>
		</div>
	</div>
</nav>