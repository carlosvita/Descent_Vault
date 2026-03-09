```dataview
LIST from "" 
WHERE contains(file.tags, "monster") 
AND !contains(file.path, "Templates")
SORT file.name ASC
````