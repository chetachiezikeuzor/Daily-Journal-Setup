---
tags: utility
aliases:
  - null
cssclass: null
---

# Using The Dataview Plugin

`Dataview` is pretty cool because you can create your own `YAML` header information and query it.  The reason I couple this with the daily journal setup is because you can find handy information from all of your daily notes. You can create a query that find all outgoing links, tags, aliases etc.

The plugin is a super simple setup. Just install it and learn it's syntax. 

![[Dataview Dailies.png]]

You can use this query if you'd like!

```
```dataview
table tags as "🔖 Tags", aliases as "📌 Aliases"
where file.day and file.ctime.month > 3
sort file.ctime asc```
```