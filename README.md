CSS Cursors
================

This is a showcase wrapping the different cursor properties you can set via CSS. 

http://css-cursor.techstream.org/

Add New Cursor
--------------

To add a missing cursor, insert an entry into <code>cursors</code> array in <code>script.js</code>. <br/>
Entry should includes the following.
<ul>
	<li>Name : Value of CSS property</li>
	<li>Browser support : Boolean. If no value is specified for a browser it will be interpreted as not supported.</li>
</ul>

example :
<pre><code>
	{ 
		"name" 				: "auto", 
		"chrome" 			: 1, 
		"firefox"	    	: 1, 
		"safari"			: 1, 
		"opera" 			: 1, 
		"internet-explorer" : 1,
		"edge"				: 1
	}
</code></pre>

Credits
-------
<ul>
	<li><strong>Headings</strong> : <a href="https://www.google.com/fonts/specimen/Merriweather+Sans">Merriweather Sans</a> for large text as they are legible themselves without the requirement of serifs, Merriweather is released in <a href="http://scripts.sil.org/OFL">SIL Open Font License, 1.1</a></li>

	<li>For body and content : <a href="https://www.google.com/fonts/specimen/Merriweather">Merriweather</a> the serif version of Merriweather, its a font designed to be a text face that is pleasant to read on screens, its also released in <a href="http://scripts.sil.org/OFL">SIL Open Font License, 1.1</a></li>

	<li><strong>Front-end Framework</strong> : <a href="http://foundation.zurb.com/learn/brands.html">Foundation</a> from Zrub. <a href="http://opensource.org/licenses/MIT">MIT License</a></li>
</ul>
