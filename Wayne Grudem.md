---
name: Wayne Grudem
aliases: 
type: Person
tags:
  - faith
  - faithfaith/doctrine
image: https://upload.wikimedia.org/wikipedia/commons/1/17/Wayne_Grudem_Photo_2014.jpg
---

![|200](https://upload.wikimedia.org/wikipedia/commons/1/17/Wayne_Grudem_Photo_2014.jpg)

## About

Wayne A. Grudem is a New Testament scholar turned theologian, seminary professor, and author. He co-founded the Council on Biblical Manhood and Womanhood and served as the general editor of the ESV Study Bible.

```dataview
TABLE WITHOUT ID
("![|50](" + image + ")") as Image, 
"[[" + file.name + "|" + title + "]]" as Title,
type as Type,
("#" + join(tags, " #")) as Tags
WHERE this.file.name = author
```
