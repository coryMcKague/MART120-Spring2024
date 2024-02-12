---
title: More form elements
module: 6
jotted: true
---

# More form elements

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Dropdown')">Dropdown List</button>
  <button class="tablinks" onclick="openTab(event, 'Radio')">Radio Buttons</button>
  <button class="tablinks" onclick="openTab(event, 'Checkbox')">Checkboxes</button>
  <button class="tablinks" onclick="openTab(event, 'ToDo')">To Do</button>
    
</div>

<!-- Tab content -->
<div id="Dropdown" class="tabcontent" style="display:block">
<iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=58df56c3-ec9b-441f-9af3-b11401447c2a&autoplay=false&offerviewer=false&showtitle=false&showbrand=false&captions=false&interactivity=none" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe>
<!-- dropdowns -->

<p>One of the most common form elements is the drop-down list.  It looks something like this.</p>

<div class="tabhtml" markdown="1">

```html
<select>
  <option value="apples">Apples</option>
  <option value="oranges">Oranges</option>
  <option value="grapes">Grapes</option>
  <option value="pineapple">Pineapple</option>
</select>
```

</div>

These allow us to restrict what the user can choose and helps us make sure we get data precisely the way we want it. If we use a text box for everything, then our users could type anything they wanted.  For example, they might say <b>Apple</b>, or <b>aPpple</b>, or <b>APPLE</b>, and that would be bad.
</div>

<div id="Radio" class="tabcontent">

<!-- video -->


<!-- radio -->
<b>What other items can you find in forms?  I spoke of radio buttons and checkboxes in an earlier section.  How would you implement a radio button list?</b>

<div class="tabhtml" markdown="1">

```html
<input type="radio" name="color" value="blue">Blue<br>
<input type="radio" name="color" value="red">Red<br>
<input type="radio" name="color" value="green">Green<br>
<input type="radio" name="color" value="purple">Purple
```

</div>

</div>

<div id="Checkbox" class="tabcontent">

<!-- video -->


<!-- checkboxes -->
<p>Finally, let's look at checkboxes and the role they play in forms.  They allow us to select multiple items in a list.  We see these most often when a form asks us what our interests are.  It may look something like this.</p>

<div class="tabhtml" markdown="1">

```html
<h2>What kind of bikes do you like?</h2>
<input type="checkbox" name="mountain" value="mountain">Mountain<br>
<input type="checkbox" name="road" value="road">Road<br>
<input type="checkbox" name="cross" value="cross" checked>Cross<br>
<input type="checkbox" name="fattire" value="fattire" checked>Fat Tire<br>
<input type="checkbox" name="gravel" value="gravel" checked>Gravel<br>
```

</div>

</div>

