# Homebrew-Recipe-Generator

The goal of this web app will be for users to generate and save their conceptual ideas for a beer as real homebrewing recipes with grain bills, brew times, and hop bills. Users will have a profile where they can share, and favorite recipes. 

Homebrewing enthusiasts or people new to homebrewing and want to get hier toes wet. The goal of the site will be to try to  take abstract artistic ideas for a brew and turn it into a step by step recipe. 

I plan to use data from a brewing archive api that includes beer stats such as ABV, IBU, SRM, grain, and hop bills. 

The database schema will have user and recipes models. They will have a one to many relationship. This will be the base schema that I might expand on in the future when I add more features. 

I think the biggest issue will be being able to get hold of all the information that I need to generate a recipe. 

This site will have no sensitive information beyond users passwords which I can hash. 

I want to focus on the basic functionality at first so a user will be able to log on or register. Generate a recipe, save it, see a list of all recipes made on the site, and favorite other users recipes. 

I plan on implementing a feature where users will be able to download recipes in a PDF format. 

Stretch goals might be sending queries to youtube from user submitted forms and getting brewing videos for techniques they have questions about. Also scraping the BJCP association site for template recipe ideas based on user submitted forms and routing those users to the template generated from the BJCP site.   
