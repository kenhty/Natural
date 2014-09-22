Best view in Firefox with flexbox enabled. Webkit browser need to fix a bug in order to view the perfect vertical rhythm. 

Additional polyfills need to make older browsers to work.

## Features:

* Modular CSS framework
* 1.6180339887498948482rem line height
* golden ratio pull-quote width
* 1 to 12 equal division column grid powered by CSS3 flexbox
* 1 to 4 golden ratio division column grid powered by CSS3 flexbox
* Fibonacci sequence in h1 h2 h3 h4 h5 h6 and other helper like .h0 - .h6
* Use 1em or 16px for readable text
* Use normalize.css
* Use CSS variable
* Media object
* incremental leading below 16px
* Responsive support for 300px, 748px, 978px, 1218px and 1378px

### Include Natural in your page

	<link rel="stylesheet" href="natural.css">

### Golden ratio grid

	<nav class='block'>
		<div class='golden-unit size1of4'>
			<p class='text-centering'>g1</p>
		</div>
		<div class='golden-unit size2of4'>
			<p class='text-centering'>g2</p>
		</div>
		<div class='golden-unit size3of4'>
			<p class='text-centering'>g3</p>
		</div>
		<div class='golden-unit size4of4'>
			<p class='text-centering'>g4</p>
		</div>
	</nav>	
	
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
		<div class='container'>
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
		<div class='container'>
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
		<div class='container'>
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
		<div class='container'>
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

### Media object	
	
	<div class='media'>
		<img src='http://placekitten.com/96/139' alt='' class='media_img'>
		<p class='media_body'>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec porttitor lacinia turpis nec pulvinar. Duis consequat tincidunt odio, non molestie purus tempus eget. Aliquam nec nisi non lacus auctor semper nec ac felis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec porttitor lacinia turpis nec pulvinar. Duis consequat tincidunt odio, non molestie purus tempus eget.</p>
	</div>