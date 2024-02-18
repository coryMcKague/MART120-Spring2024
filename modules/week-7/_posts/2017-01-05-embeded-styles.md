---
title: Embedded Styles
module: 7
jotted: true
---

# Adding CSS to HTML

## Embedded

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
   <button class="tablinks" onclick="openTab(event, 'Embedded')">Embedded Style</button>
   <button class="tablinks" onclick="openTab(event, 'ToDo')">To Do</button>
    
</div>

<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">

<p><iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=790f7561-4e2c-41d7-8c5a-b11a01258bdd&autoplay=false&offerviewer=true&showtitle=false&showbrand=false&captions=false&interactivity=none" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe></p>

<p>The second way in which we can add CSS by using <b>embedded</b> styles on the page.  By having embedded styles, we apply a format to only this page.</p>

</div>

<div id="Embedded" class="tabcontent">

<p>An example might look like this.</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <head>
        <title>Embedded Style Example</title>
        <!-- notice the style tag is in between the open and closed head tag -->
        <!-- this is an example of an embedded style because it is 
        between the style tags -->
       <style> 
        
            span{
                background-color:red;
            }
        </style>
       
    </head>
    <body>
        <span>This is the first sentence.</span> 
        <br />
            This is the second sentence.
        <br />
        <span>This is the third sentence</span>
    </body>
</html>
```

</div>

<p>*Note - a <b>span</b> tag is a tag that can be included inline with other text. It's allows us to style text that is inline with other text. In this example, you see the first, and the third sentence has a background color of red. While the second sentence does not.  The style at the top of the page within the <b>&lt;head&gt;</b> tags applies the background color to all span tags.</p>

<p>What are some of the positives and negatives of using embedded styles?</p>

</div>
<div id="ToDo" class="tabcontent">
<p class="codepen" data-height="600" data-default-tab="html,result" data-slug-hash="wvebovq" data-editable="true" data-user="coryMcKague" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/coryMcKague/pen/XWGOyZX">
  </a> by Cory McKague (<a href="https://codepen.io/coryMcKague">@coryMcKague</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
</div>