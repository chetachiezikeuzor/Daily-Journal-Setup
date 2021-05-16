---
tags: utility
aliases:
  - null
cssclass: null
---

# Using the Templater Plugin

The `Templates` plugin recently had a new syntax change, so your daily template may look a little funky. Set a dedicated folder for your templates, including your daily notes template(s). 

![[Templates Location.png]]
Now, in my templates, I created `HTML` buttons elements to keep all my days connected to one another. You can reference "Yesterday" & "Tomorrow" easily with. Feel free to change the buttons to plain `Wikilinks` as you wish, but the syntax below will tell `Templater` to link to the given day.  

- <% tp.date.yesterday() %>
- <% tp.date.tomorrow() %>