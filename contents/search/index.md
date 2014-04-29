---
layout: main
title: Adding A Search Bar
---

# Adding A Search Bar

Everyone loves to share images online! With the `<img>` tag, you can put images in your own web pages! 

The code for creating a search bar is already in the Tumblr code, you just need to find it, it will be contained within comment codes: 
<pre><xmp> <!-- CODE HERE -->
</xmp></pre>
You should delete the <pre><xmp> <!-- </xmp></pre>

The Tumblr documentation on search is available [here](http://www.tumblr.com/docs/en/custom_themes#search). You should look for the code shown in the example in your tumblr theme:
<pre><xmp>
<form action="/search" method="get">
    <input type="text" name="q" value="{SearchQuery}"/>
    <input type="submit" value="Search"/>
</form>
</pre></xmp>

<a href="../search_solution"><button type="button" class="btn btn-primary btn-lg">Having trouble? Click here for a solution.</button></a>
  
---

<div class="row">
  <div class="col-md-1">
    <a href="../imageborder"><button type="button" class="btn btn-primary btn-lg">Back</button></a>
  </div>
  <div class="col-md-1">
    <a href="../likes"><button type="button" class="btn btn-primary btn-lg">Next</button></a>
  </div>
</div>

---