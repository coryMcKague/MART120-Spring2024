---
title: HTML Forms
module: 6
jotted: true
---

# HTML Forms

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
  <button class="tablinks" onclick="openTab(event, 'Example')">Example</button>
  <button class="tablinks" onclick="openTab(event, 'ToDo')">To Do</button>
    
</div>

<!-- Tab content -->
<div id="Overview" class="tabcontent" style="display:block">

<iframe src="https://umontana.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=9d805f27-2774-4acc-a5a7-b11401447bce&autoplay=false&offerviewer=false&showtitle=false&showbrand=false&captions=false&interactivity=none" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay" aria-label="Panopto Embedded Video Player"></iframe>

<p>What are HTML forms?  If you have ever purchased something online or filled out an application online or signed up for an email, your social media account, or more, you have filled out a form.  Forms are just a way for us to gather data from the end-user.  Keep in mind there are some principles to which we should adhere.</p>

<p>First, we want to adhere to standards. Use the component for their intended use.  Use checkboxes for multiple selections and radio buttons for various choices, but only one correct one.</p>

<p>Aso, use dropdown lists, use those to control the input gathered.  We are going to first focus on creating forms and what tags are required. Then, we will add a look and feel to them and add a little functionality to them.</p>

</div>

<div id="Example" class="tabcontent">

<p>Here is an example of a simple form.</p>

<div class="tabhtml" markdown="1">

```html
<html>
    <head>
        <title>My first page</title>
    </head>
    <body>
        
        <form action="nextPage.html" type="POST">
            First Name: <input type="text" id="fName"><br>
            Last Name: <input type="text" id="lName"><br>
            <button id="mySubmit" type="submit">Submit</button>
        </form>
    </body>
</html>

```

Notice, we are using different attributes now.  We have the **action**, **type** and **id**.  These attributes just let the browser know where the form is going to go after the button is clicked -- **action** -- and how the form data will be stored when it goes to the other page **type="POST"** For the textboxes, the **type** is text and the **id** gives us a way to access the information.  We will go deeper into this when we get to JavaScript.  Finally, the button type **submit** just means the form will perform its action.
</div>

</div>
