---
layout: main
title: Changing Link Color
---

# Changing the Color of Links

Remember, the code to create a link is <pre><xmp> <a href="[URL HERE]"/> </xmp></pre>
Thus, you're looking in the CSS for the a, a:hover, and a:visited selectors.

<div class="row">
  <div class="col-md-6">

    <div class="panel panel-primary">
      <div class="panel-heading">
        <h3 class="panel-title">Code</h3>
      </div>
      <div class="panel-body">
        <pre><code>
     &lt;style&gt;
      body { 
        margin: 0; 
        padding: 20px;
        <b>background-color: <i>green</i>; </b>
        font-family: arial;
        font-size: 0.75em;
        color: blue;
      }
     <b> a {  //this is the link as you see it on the page
			  color: black;
			  text-decoration: underline;
		  }
		
	  	a:hover {	//this is the link when the mouse is hovering over it
			  color: white;
			  background: red;
		  }
			
		  a:visited{	//this is the link after it is visited
		    color:blue;
		  }</b>

          </code></pre>
      </div>
    </div>
  
  </div>
</div>

You want to change the code in the bold section. You can use the color selector to refer to the text color, see [here](http://mcwic.github.io/htmlblocks/htmlBuildingBlocks.html) and [here](https://www.youtube.com/watch?v=n9HoTInjjUs&index=9&list=PLPpkJJSKXEJ11Mq8xjty3AZKldH9V48mt) for more information on CSS font attributes.
---

<div class="row">
  <div class="col-md-1">
    <a href="../linkcolor"><button type="button" class="btn btn-primary btn-lg">Back</button></a>
  </div>
</div>

---