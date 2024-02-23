---
title: Variables
module: 8
jotted: true
---

# Variables

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
   <button class="tablinks" onclick="openTab(event, 'Example')">Variables Example</button>
   <button class="tablinks" onclick="openTab(event, 'HTML')">HTML Example</button>
   <button class="tablinks" onclick="openTab(event, 'ToDo')">To Do</button>
    
</div>
<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">
<iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=76ef587d-b390-4c56-9016-b11f014a32d9&autoplay=false&offerviewer=true&showtitle=false&showbrand=false&captions=false&interactivity=none" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe>

<p>So, you have been working with variables in all the other languages with which we have worked. Hopefully, these won't feel scary or foreign to you now.</p>
</div>
<div id="Example" class="tabcontent">

<p>What do they look like in JavaScript?</p>

<div class="tabhtml" markdown="1">

```js
 var favoriteNumber = 13;
 var favoriteColor = "blue";
 var myAge;
 myAge = 79;
 var red,green,blue;
 red = "#FF0000";
 green = "#00FF00";
 blue = "#0000FF";
```

</div>
</div>
<div id="HTML" class="tabcontent">
<p>As you stated above, there are several different ways in which you can declare and assign values to your variables. They are all valid, and it just depends on when you want to give them a value or if they will be assigned later.</p>

<p>To use them in your HTML page, you can do something like this.</p>

<div class="tabhtml" markdown="1">

```html
 <html>
    <title>Variables</title>
    <head>
    <script>
        var favoriteColor = "blue";
    </script>
    </head>
    <body>
        <span id="myTag">This is my favorite text</span>
    </body>

    <script>
        document.getElementById("myTag").innerHTML = "Favorite Color " + favoriteColor;
    </script>
 </html>
```

</div>

<p>There are three things to notice here.</p>
<ol>
<li>I can put the variable in the script tag inside the head tag because it is not trying to access the tag <b>myTag</b>.</li>
<li>When I print out the variable <b>favoriteColor</b>, it has to precisely match the capitalization as it is declared or not work.</li>
<li>To make it show up in the tag, you have to use the <b>+</b> and then put the variable name without the double-quotes <b>"</b>. The double-quotes are required if you want to print out exactly what is inside the double-quotes. In this case, we want to print out the value stored in the variable.</li>
</ol>
</div>

<div id="ToDo" class="tabcontent">
<p class="codepen" data-height="600" data-default-tab="html,result" data-slug-hash="jOLWrmb" data-editable="true" data-user="coryMcKague" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/coryMcKague/pen/GRebWzG">
  JS - Variables</a> by Cory (<a href="https://codepen.io/coryMcKague">@coryMcKague</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
</div>