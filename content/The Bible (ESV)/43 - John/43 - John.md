---
folder: The Bible
---

```dataview
LIST 
WHERE contains(Aliases, "John") AND !contains(Aliases, "1 ") AND !contains(Aliases, "2 ") AND !contains(Aliases, "3 ")
SORT number(replace(file.name, "John ", "")) ASC
```
 
