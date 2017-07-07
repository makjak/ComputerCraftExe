# ComputerCraftExe
Various scripts for ComputerCraft 1.75

## Maker
Allows to make recipes on computers and turtles.

Requirements:
 * STD
 * Forms
 * STDTurtle (optional)

Usage:
`maker [-h] recipe`
 * `-h`: Show help
 * `recipe`: Recipe path

 
## Craft
Automatically craft items using recipes made with Maker.

Requirements:
 * STD
 * STDTurtle

Usage:
`craft recipeFolder finalRecipe amount [-t]`
 * `recipeFolder`: Folder path that contains all the recipes
 * `finalRecipe`: Recipe file (not path) that will be crafted contained in the recipe folder
 * `amount`: How many items to craft
 * `-t`: Only shows the requirements combinations
