<h1>Robin&#39;s LightBox!</h1>
<p>The objective of this LightBox is to be simple, and to stay simple! In it's current state, there are only 4 options; URL, width, height and border.</p>
<p>LightBox is called from a javascript event. This means you can call LightBox from anything from a button through to an image. For the best results use an 'OnClick' event, but it should work with any of them, you can read more on w3schools: <a href='http://www.w3schools.com/jsref/dom_obj_event.asp' target='_new'>http://www.w3schools.com/jsref/dom_obj_event.asp</a>
<h2>Setup instructions</h2>
<ul>
<li>Place the LightBox folder in your web directory.</li>
<li>Insert the following code into your HTML just before the &lt;/body&gt; tag. (make sure you change "src" to the relative location to your HTML)<pre>&lt;script type="text/javascript" src="Path/To/LightBox/lightbox.wrapper.js"&gt;&lt;/script&gt;</pre></li>
<li>Setup complete! test LightBox out by copying the examples in the examples directory. It's as simple as:<pre>&lt;a class='demoButton' href="javascript:void(0)" onclick="openwrapper('http://example.com',640,480);"&gt;Open LightBox!&lt;/a&gt;</pre></li>
<li>In a production environment you should delete the example directory.</li>
</ul>
