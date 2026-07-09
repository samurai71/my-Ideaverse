---
obsidianUIMode: preview
banner: "![[pexels-rfera-2286895.jpg]]"
banner_y: 0.48388
---

Your launchpad and home base. That's here. That's **home**.

 # Recent Thoughts or Notes

> [!activity]- ## Added Stuff
> This view looks at the 10 newest notes in your **+** folder. As you process each note: add a link, add details, move them to the best folder, and delete everything that no longer sparks ✨.
>
> ```dataview
> TABLE WITHOUT ID
>  file.link as "",
>  (date(today) - file.cday).day as "Days alive"
>
> FROM "+" and -#x/readme
>
> SORT file.cday desc
>
> LIMIT 10
> ```


> [!activity]+ ## Collections
>
>
> [[Books]]
>  [[Movies]] 
>  [[Recipes MOC]] 



## Web Development

[[Checklist's Template]]
[[Policy Templates]]
[[Github Templates]]

## My Medical Information
[[My Medical]]

## Shell Stuff
[[ZSH Shortcuts for my setup]]
[[PNPM shortcuts for my setup with a plugin]]











