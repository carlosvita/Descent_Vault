```dataview
LIST from ""
WHERE contains(Type, "campanha") 
AND !contains(file.path, "Templates")
SORT file.name ASC
````