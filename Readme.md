MyMixology
External API: https://www.thecocktaildb.com/

Description
MyMixology is web application that contains hundreds of drink recipes including cocktails, mocktails, and shakes to name a few. Users may create an account to bookmark recipes at their leisure. However, access to the recipes is not limited to account holders. Users may refine their searches by applying filters in the search form.

Features
Search form allowing filtering by name, ingredient, or category.
Filters can be chained.
Allows for ease of access to recipes meeting specific criteria.
Seed data from API filtered with better-profanity library to avoid recipes containing profanity.
Multilingual instructions, where provided by the API.
User accounts
Login and registration handled on server side with use of Flask and WTForms.
Can bookmark recipes to easily access them when logged in.
Not required to access recipes.
User Flow
Guest users have all recipes at their disposal, and may opt to register via the navigation bar's "Register" link. To register, users must specify a username, password, and a language preference of their choosing. This will default to English.

Furthermore, registered users must log in to access bookmarking features. When saving a recipe, one must flick the bookmark icon located under the drink's title on the recipe page.

Bookmarked recipes can be found and removed on the user's profile, where the user's account information is also displayed. Here, the logged in user may delete their account altogether.

Tech Stack
Languages:
HTML5
Python
JavaScript
PostgreSQL
Libraries/Tools:
Axios
Bcrypt
Better-Profanity
Flask
Flask-DebugToolbar
Jinja2
jQuery
SQLAlchemy
Unittest
WTForms

