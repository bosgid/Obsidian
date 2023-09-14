
```start-multi-column
ID: ID_supz
Number of Columns: 2
Largest Column: standard
```

## Old Testament
```dataview
LIST WITHOUT ID "[[" + file.name + "|" + regexreplace(file.name, "\d\d -", "") + "]]"
WHERE folder = "The Bible"
SORT number(regexreplace(file.name, "[- ].*", "")) ASC
LIMIT 39
```

--- column-end ---

## New Testament
```dataview
LIST WITHOUT ID "[[" + file.name + "|" + regexreplace(file.name, "\d\d -", "") + "]]" 
WHERE folder = "The Bible" AND number(regexreplace(file.name, "[- ].*", "")) > 39
SORT number(regexreplace(file.name, "[- ].*", "")) ASC
```

--- column-end ---

--- end-multi-column









 
