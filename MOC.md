---
tag:
cssclasses:
  - optional-full-width
  - callout-ruler
  - justified
---

<div style="text-align:center">
 <img src="https://static.wikia.nocookie.net/descent2e/images/a/a6/Descent-logo.png/revision/latest?cb=20140103173652">
</div>

<br>

> [!cards|5]
> **CAMPANHAS**
> ![[1396111400-lair-of-the-wyrm-by-belibr-d5s7mfi.jpg|sban htiny ctr]]
>
> **[[GUIA DE REFERÊNCIA|Guia de Referência]]**
> ![[d57uqpv-7ae64507-88ee-43d9-8cd2-9d91d5ac6546.jpg|sban htiny ctr]]
>
> **[[Fluxo de Campanha D2ed|Fluxo de Campanha]]**
> ![[lor-cover-e1497734555752.webp|sban htiny ctr]]
>
> **[[Mapa de Terrinoth]]**
> ![[Baronies_of_Terrinoth_-_Borders.jpg|sban htiny ctr|sban htiny ctr]]
> 
> **CAMPANHAS**
> ![[Trollfens.jpg|sban htiny ctr]]


> [!custom-tent]- Campanhas
>```datacards
>TABLE replace(replace(cover, "[[", ""), "]]", "") as cover
>FROM ""  
>WHERE !contains(file.path, "Templates")
>AND contains(Type, "campanha")
>SORT file.name asc
>
>// Settings
>preset: card
>columns: 6
>imageProperty: cover
>imageHeight: 20px
>cardSpacing: 4
>```
> 

<div class="homepage">
<hr>
</div>


> [!custom-skull]+ Monstros
>```datacards
>TABLE cover, trait FROM #monster 
>WHERE !contains(file.path, "Templates")
>SORT file.name asc
>
>// Settings
>preset: square
>columns: 6
>imageProperty: cover
>showImageOnHover: true
> cardSpacing: 4
> ```
---




