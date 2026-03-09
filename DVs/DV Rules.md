```dataview
LIST from ""
WHERE contains(file.tags, "rules") 
AND contains(Type, "resources") 
AND !contains(file.path, "Templates")
SORT file.name ASC
````