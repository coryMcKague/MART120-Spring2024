---
title: Hyperlinks
module: 6
jotted: true
---

# Hyperlinks

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
  <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>

  <button class="tablinks" onclick="openTab(event, 'ToDo')">To Do</button>
    
</div>

<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">
<!-- video -->
<iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=3673d502-a9f8-4ac8-bf39-b111017507b5&autoplay=false&offerviewer=true&showtitle=false&showbrand=false&captions=false&interactivity=none" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe>

<p>Hyperlinks have been around since the beginning of HTML4 and continue today. They are the bedrock of web pages as they take us places.  They have a similar structure to image tags, and they look like this.</p>

<div class="tabhtml" markdown="1">

```html
<a href="mypage.html">Link to somewhere</a>
```

</div>

</div>

<div id="Description" class="tabcontent">

<p>The <b>&lt;a&gt;</b> tag is called the anchor tag.  It tells us that there will be a link there.  The <b>href</b> is the attribute that indicates where you are going to go.  So in the previous instance, if we clicked on the <b>Link to somewhere</b>, it would take us to the <b>mypage.html</b> page.</p>

<p>So, how does the whole page look?</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <head>
        <title>My first page</title>
    </head>
    <body>
        <a href="secondpage.html">Go to my other page</a>
    </body>
</html>

```

</div>

<p>Whereas on the second page, you might have something that looks like this.</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <head>
    <title>My second page</title>
    </head>
    <body>
        <a href="firstpage.html">Go to my first page</a>
    </body>
</html>

```

</div>

<p>Keep in mind that you have to have two pages named <b>secondpage.html</b> and <b>firstpage.html</b>, respectively.</p>

</div>

<div id="ToDo" class="tabcontent">

<p class="codepen" data-height="600" data-default-tab="html,result" data-slug-hash="ExXMOLE" data-editable="true" data-user="retrog4m3r" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/coryMcKague/pen/XWGxJbx">
  Hyperlinks</a> by Cory McKague (<a href="https://codepen.io/coryMcKague">@coryMcKague</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

</div>