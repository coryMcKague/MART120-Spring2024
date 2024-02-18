---
title: External Style Sheets
module: 7
jotted: true
---

# Adding CSS to HTML

## External Style Sheets

<div class="tab">
    <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
    <button class="tablinks" onclick="openTab(event, 'Stylesheet')">External Stylesheet</button>
    <button class="tablinks" onclick="openTab(event, 'Page')">HTML Page</button>
    <button class="tablinks" onclick="openTab(event, 'Order')">Ordering of Styles</button>
   
</div>

<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">

<p><iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=cd57bb8c-11b5-4c57-bb2c-b11a01258c49&autoplay=false&offerviewer=true&showtitle=false&showbrand=false&captions=false&interactivity=none" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe></p>

<p>The last way in which we can apply a style is through an <b>external</b> style sheet.</p>

</div>

<div id="Stylesheet" class="tabcontent">

<p>How does the stylesheet look?</p>

<div class="tabhtml" markdown="1">

```css
/* 
This is what will go inside the external style sheet
Notice that the <style> tags are not required here
*/
span{
    color:white;
    background-color:red;
}
```

</div>

<p>Note that when you save this on a separate page, it must be called <b>mainstyle.css</b>  It always ends with a <b>.css</b> extension.</p>

</div>

<div id="Page" class="tabcontent">

<p>Now, we can assign it to a page like this.</p>

<div class="tabhtml" markdown="1">

```html
    <html>
        <head>
            <title>External Style Sheet</title>
            <!-- This link tag allows us to connect the HTML page to the external stylesheet -->
            <!-- Once again, notice this is in between the head tags of the HTML page -->
            <link rel="stylesheet" type="text/css" href="mainstyle.css">
        </head>
    </html>
```

</div>

<p></p>

<p>There are a couple of things to note.  The <b>rel</b> is the relationship attribute, and the <b>type</b> specifies the type of file.  Finally, the <b>href</b>, which should look familiar, is the file location. Remember, if it defined like it is above, it has to be in the same folder.  Otherwise, you need to add the correct relative path. *Remember: A relative path is something that is relative to the page is linking to it versus an absolute path is one that contains the full path the file on one's computer.</p>

<p>We use style sheets so that we can apply a style sheet to many pages.  If we want to make a change, we can change it in one file and use it everywhere.</p>

</div>

<div id="Order" class="tabcontent">

<p>So, when you have all three types of styles on your page, which style is applied?  It always goes in this order.</p>

<ol>
<li>Inline styles first</li>
<li>Embedded</li>
<li>External</li>
<li>Browser</li>
</ol>

<p>Yes, that's right; the browser has a style sheet.  If you are interested, take a look around, and you can find and change your browser's style sheet. Fun right?</p>

</div>

