---
up:
  - "[[Home]]"
related:
  - Recipes
in:
  - Collections
  - Recipes
---
```meta-bind-button
label: New Recipe
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: templaterCreateNote
    templateFile: x/Templates/Template, Recipe.md
    folderPath: Atlas/Dots/Collections/Recipes
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```

```dataview
LIST
FROM "Atlas/Dots/Collections/Recipes"
Limit 10
```