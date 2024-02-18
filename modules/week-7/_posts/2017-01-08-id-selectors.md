---
title: ID Selectors
module: 7
jotted: true
---

# ID Selectors

<div class="tab">
    <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
    <button class="tablinks" onclick="openTab(event, 'HTML')">HTML Example</button>
    <button class="tablinks" onclick="openTab(event, 'CSS')">ID Selectors Example</button>
    <button class="tablinks" onclick="openTab(event, 'ToDo')">To Do</button>
</div>

<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">

<p><iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=c8236724-b7b9-4bce-8f0b-b11a01257edb&autoplay=false&offerviewer=true&showtitle=false&showbrand=false&captions=false&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe></p>

<p>Another way in which we can select a tag is by their ID if they have an id attribute defined. </p>

</div>

<div id="HTML" class="tabcontent">

<p>The HTML page might look like this.</p>

<div class="tabhtml" markdown="1">

```html
    <html>
        <head>
            <title>id Example</title>
            <link rel="stylesheet" type="text/css" href="mainstyle.css">
        </head>
        <body>
            <span id="specificColor">New Color</span>
            <br>
            <span>Same Color</span>
            <br>
            <a href="https://www.amazon.com" id="specificLink" target="_blank">Amazon</a>
        </body>
    </html>
```

</div>

</div>

<div id="CSS" class="tabcontent">

<p>And the CSS might look like this.</p>

<div class="tabhtml" markdown="1">

```css
    #specificColor{
        color:blue;
        font-family:verdana;
        font-size:24px;
    }

    #specificLink{
        color:red;
        font-family:arial;
        font-size:28px;
    }
```

</div>

<p>This time, the color and the size of the text specific to the ID because of the <b>#</b>.</p>

</div>
<div id="ToDo" class="tabcontent">
<p class="codepen" data-height="600" data-default-tab="html,result" data-slug-hash="mdwYOVO" data-editable="true" data-user="coryMcKague" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/coryMcKague/pen/vYPPJKa">
  id Selector</a> by Cory McKague (<a href="https://codepen.io/coryMcKague">@coryMcKague</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
</div>