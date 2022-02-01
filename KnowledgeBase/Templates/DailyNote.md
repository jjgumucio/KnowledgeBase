```
← [[Daily/<% tp.date.now("YYYY/MM-DD", -1,  (tp.file.folder() + "/" + tp.file.title), "YYYY/MM-DD") %> | <% tp.date.now("MM-DD", -1,  tp.file.title, "MM-DD") %>]] | <% tp.file.title %> | [[Daily/<% tp.date.now("YYYY/MM-DD", 1, (tp.file.folder() + "/" + tp.file.title), "YYYY/MM-DD") %> | <% tp.date.now("MM-DD", 1, tp.file.title, "MM-DD") %>]] →

# <% tp.date.now("dddd, MMMM D YYYY", 0,  (tp.file.folder() + "/" + tp.file.title), "YYYY/MM-DD") %> 
```