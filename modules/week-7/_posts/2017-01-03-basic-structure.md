---
title: Basic Structure of CSS
module: 7
jotted: false
---

# Basic Structure of CSS

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
   <button class="tablinks" onclick="openTab(event, 'Example')">Example</button>
    
</div>

<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">
<!-- video -->
<p><iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=ca91cbe4-5bfd-46a2-ad2a-b11a01257e4b&autoplay=false&offerviewer=true&showtitle=true&showbrand=true&captions=false&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe></p>

<p>In its most basic form, CSS looks like this.</p>

<p><img src="../imgs/selector.gif" alt="selector" /></p>

<p>The description is as follows.</p>
<ol>
<li>The selector points to the HTML element you want to style.</li>
<li>The declaration block contains one or more declarations separated by semicolons.</li>
<li>Each declaration includes a CSS property name and a value, separated by a colon.</li>
<li>End CSS declarations with a semicolon</li>
<li>Surround declaration blocks by curly braces</li>
</ol>
<p><i>source - <a href="http://w3schools.com" target="_blank">w3schools.com</a></i></p>
</div>
<div id="Example" class="tabcontent">

<p>For example, you might have a style that looks like this.</p>

<div class="tabhtml" markdown="1">

```css

body {
  bgcolor: pink;
  text-align: center;
}

```

</div>

<ol>
<li>body is the <b>selector</b></li>
<li>bgcolor and text-align are part of the <b>declaration</b> and is the <b>CSS property name</b>.  The <b>declaration block</b> contains the declarations separated by a semicolons <b>important!</b>. <b>{ }</b> braces surround the declaration block.</li>
<li>Finally, <b>pink</b> and <b>center</b> are also part of the <b>declaration</b> but are the <b>values</b> of the properties.</li>
</ol>
</div>