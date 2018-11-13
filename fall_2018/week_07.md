## Last Week's Accomplishments

> In this section, you can write about what you accomplished in the previous week.

> Examples:
> Bug fixes, Features added, Links to Issues, Links to Pull-Requests, Lightning Talks, Bonus Sessions

This week, I read up on documentation of Atom styling. I learned that Atom styling is done using ui themes and
syntax themes. For this project, we will be working mostly with ui-theming. UI-theming is done with Less, which
is a superset of CSS that includes variables, functions, etc. and can run any CSS syntax as well. It is technically
a Javascript library. I also read up on CSON files and how they differ from JSON files. CSON files are a lot more 
concise, since they don't use curly braces, and they also don't use commas or quotes for keys. To handle showing 
instructions on screen, we will be using CSON files, which we can either write directly, or convert from JSON files
using the json2cson command included in the cson package.

## This Week's Plan

> In this section, you can write about what you have planned for next week.

> Examples: New Bugs to be fixed, Design choices

This week, I plan on adapting the styling of the plugin to conform with Less conventions, and using Atom included
styling cues, such as buttons, fonts, and colors, to make the plugin seem more like an integrated part of Atom.

## Anything Blocking?

> In this section, you can write about any blockers that you are having trouble in the project.

> Examples: Confusion on how to approach a problem, Limited experience with a specific technology

The main instructions section still does not show up when the plugin is loaded, but we now have a way to force
reload the plugin without restarting Atom, which should make debugging a lot quicker and smoother. 

## Notes

> This is an optional section for any sort of information that does not fall under any of the other categories.
