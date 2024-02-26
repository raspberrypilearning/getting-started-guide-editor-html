## The Code and Preview panels

## The Code panel

At the top of the panel is the file name. 

In this example, the file name is `index.html`

The Code panel includes the following features: 

--- collapse ---
---
title: Line numbering
---

When you type new lines of code in the Editor, line numbers will be added for you. 

Line numbering helps you keep track of where you are in your project and helps you work with others on your code.

--- /collapse ---

--- collapse ---
---
title: Syntax highlighting
---

Syntax highlighting improves readability of code by applying colours and styles to different elements based on the language's syntax (the 'rules' of the language). 

It helps distinguish different parts of the code and is a valuable tool for developers, making code more accessible.

In this example, you can see that the Editor highlights each opening and closing tag in green. Values are highlighted in red.

![HTML code in the Editor](images/index_code.png)

--- /collapse ---

--- collapse ---
---
title: Indentation
---

The Editor will automatically format your code by adding spaces to create a visual hierarchy and structure. Indentation does not affect how the HTML document is rendered in a browser, but it helps make code more readable and easier to maintain.

In this example, you can see that the `<head>` and `<body>` elements are nested in the `<html>` tags - they are known as child elements, under the parent `<html>`

![HTML code in the Editor](images/index_code.png)

--- code ---
---
language: html
filename: index.html
line_numbers: 
line_number_start: 1
line_highlights:
---

<!DOCTYPE html>
|
└─ <html lang="en">
   |
   └─ <head>
   |  |
   |  ├─ <meta charset="UTF-8" />
   |  |
   |  ├─ <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   |  |
   |  ├─ <title>Getting Started with the Raspberry Pi Editor</title>
   |  |
   |  └─ <link rel="stylesheet" href="style.css" />
   |  
   └─ <body>
      |
      └─ <main>
         |
         └─ <p>
            |
            └─ Welcome to the Raspberry Pi Editor!


--- /code ---

--- /collapse ---

--- task ---

### Try it
<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 175px; flex-grow: 1">  

Add this HTML to your project.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights:
---

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Getting Started with the Raspberry Pi Editor</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <main>
      <p>
        Welcome to the Raspberry Pi Editor!
      </p>
    </main>
  </body>
</html>

--- /code ---

**Notice** the line numbering, syntax highlighting and indentation.

**Test:** 

+ Click the **Run** button.
+ Your code will be rendered in the Preview panel.

</div>
</div>

--- /task ---


--- print-only ---
![HTML code in the Code panel](images/index_code.png)
--- /print-only ---