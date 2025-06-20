---
obsidianUIMode: preview
---

Your launchpad and home base. That's here. That's **home**.

 ## Recent Thoughts or Notes

> [!activity]+ ## Added Stuff
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

## Collections

[[Books]]
[[Movies]]
[[Recipes]]
[[People Map]]


## Dev.to Blog

[[Ideas]]
[[Articles]]
	- [[Read]]
	- [[Create New Article]]


## Web Development

[[Checklists]]
[[Policies]]
[[Github Templates]]














