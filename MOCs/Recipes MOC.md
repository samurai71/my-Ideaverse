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
    templateFile: Templates/Template, Recipe.md
    folderPath: Collections/Recipes
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```

```dataview
LIST
FROM "Collections/Recipes"
Limit 10
```