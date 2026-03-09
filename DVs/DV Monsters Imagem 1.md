```dataview
TABLE
"<img src='" + cover + "' width='60' style='border-radius:4px;box-shadow:0 0 3px rgba(255, 255, 255, 0.4);'/>" AS img,
aliases AS Nome,
trait AS Trait,
abillities As Skills
FROM ""
WHERE contains(file.tags, "monster")
AND !contains(file.path, "Templates")
SORT file.name ASC
```