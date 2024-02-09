---
title: Addional Tags
module: 6
jotted: true
---

# Additional Tags

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
  <button class="tablinks" onclick="openTab(event, 'Lists')">Lists</button>
  <button class="tablinks" onclick="openTab(event, 'Images')">Images</button>
  <button class="tablinks" onclick="openTab(event, 'ToDo')">To Do</button>
    
</div>

<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">
<!-- video -->

<iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=10d39963-428c-4eb4-9cc5-b111016cbe3d&autoplay=false&offerviewer=true&showtitle=false&showbrand=false&captions=false&interactivity=none" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe>

<p>Two tags inside the <b>&lt;html&gt;</b> tag, but do not appear on the page are the title tag and the head.  The first is the <b>&lt;title&gt;</b> tag, and the second is the <b>&lt;head&gt;</b> tag.  They both exist above body tag, and they serve two very distinct purposes.</p>

<ol>
<li>title - the text that goes between the title tags show up in the tab or the title bar of the browser.</li>
<li>head - the head tag contains items like included files.  We will examine these as time goes on.</li>
</ol>
<p>Here's an example of the head and the title tags.</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <head>
        <title>My first page</title>
        <!-- this is a comment -->
        <!-- we will put stuff in here later -->
    </head>
    <body>
        This is a some random text
    </body>
</htmL>
```

</div>

<!-- video -->

</div>

<div id="Lists" class="tabcontent">

<p>There are several other tags that we use for display purposes.</p>

<ol>
<li>ol - Use this tag to create an ordered list.</li>
<li>ul - Use this tag to create an unordered list</li>
<li>li - this tag must be used with the ol and ul to make the list items appear</li>
</ol>

<p>It looks like the following:</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <title>My first page</title>
    <body>
        <ol>
            <li>Apples</li>
            <li>Oranges</li>
            <li>Grapes</li>
        </ol>

        <ul>
            <li>Dogs</li>
            <li>Cats</li>
            <li>Hedgehogs</li>
        </ul>
    </body>
</html>
```

</div>

<p>Try these tags in the section below to ensure that you see the ordered and the unordered list.</p>
</div>

<!-- video -->
<div id="Images" class="tabcontent">

<p>What else can we do?  If I want to display images, there is a unique tag for that.  It's the <b>&lt;img&gt;</b> tag.  Using this tag, we can view images. Let's look at an example, and then I will explain it to you.</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <title>My first page</title>
    <body>
        <img src="myPicture.jpg" />
    </body>
</htmL>
```

</div>

<p>What did I do? Yikes!  What I did was add what is called an <b>attribute</b> to the <b>&lt;img&gt;</b> tag.  This attribute is where we store the location of the image.  It can be on your computer or reference a picture online.  Pretty cool, huh?  There are more attributes if we want to change the size of the image as well.  They are <b>height</b> and <b>width</b>.</p>

<p>Try this example out and see if it works:</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <title>My first page</title>
    <body>
        <img src="myPicture.jpg" height='200' width='200'/>
    </body>
</htmL>
```

</div>

</div>

<div id="ToDo" class="tabcontent">
<p class="codepen" data-height="600" data-default-tab="html,result" data-slug-hash="zYzbMWp" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/coryMcKague/pen/xxByxvM">
  Additional Tags</a> by Cory McKague (<a href="https://codepen.io/coryMcKague">@coryMcKague</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

</div>