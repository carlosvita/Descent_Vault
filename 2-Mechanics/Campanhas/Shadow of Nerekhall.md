---
aliases:
tags:
  - D2ed
  - shadow_of_nerekhall
Type:
  - campanha
cover: https://cf.geekdo-images.com/uCYMit1Mhw7zvinsXoLvYw__imagepage/img/skuKlzAHUn-Cl2xnXtHl6iZkBLM=/fit-in/900x600/filters:no_upscale():strip_icc()/pic1851077.jpg
cssclasses:
---
## Quests
```tabs
tab: Ato I
```dataview
LIST
FROM ""
WHERE !contains(file.path, this.file.path)
AND !contains(file.folder, "Templates")
AND any(this.file.tags, (tag) => contains(file.tags, tag)) 
AND contains(Type, "quest")
AND contains(Ato, "I")
SORT file.name ASC

tab: Ato II
```dataview
LIST
FROM ""
WHERE !contains(file.path, this.file.path)
AND !contains(file.folder, "Templates")
AND any(this.file.tags, (tag) => contains(file.tags, tag)) 
AND contains(Type, "quest")
AND contains(Ato, "II")
SORT file.name ASC

```
## Map of Nerekhall
