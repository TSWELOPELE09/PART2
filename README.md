RecipeManager Application

The RecipeManager application is a console-based program designed to manage and scale recipes. Users can add recipes, ingredients, steps, and scale the quantities of ingredients. The application also calculates the total calories of a recipe and alerts the user if the total exceeds 300 calories.

Features

Add an unlimited number of recipes - Users can add multiple recipes, each with a unique name.
Add ingredients and steps - For each recipe, users can add ingredients with quantities, units, calories, and food groups, as well as preparation steps.
Scale recipes - Users can scale the quantities of ingredients by a specified factor.
Display recipes - Users can view a list of all recipes sorted alphabetically by name and display detailed information about any recipe.
Calorie calculation and alerts - The application calculates the total calories of a recipe and alerts the user if the total exceeds 300 calories.
Changes and Enhancements

Core Changes
Recipe Class: Introduced a Recipe class to encapsulate the details of a recipe, including its name, ingredients, steps, and scaling factor.
Enhanced Ingredient Details: Ingredients now include additional information:
Quantity
Unit
Calories
Food group
Scaling Mechanism: The scaling mechanism was updated to adjust the quantities of ingredients while keeping the calorie information intact.

Calorie Calculation: Added functionality to calculate and display the total calories of a recipe, and to alert the user if the total exceeds 300 calories.

Recipe Management: Implemented methods to add recipes, ingredients, steps, and to display recipes in alphabetical order.

User Interaction: Created a user-friendly console menu to navigate through the different functionalities of the application.

Running the Application.
The application will present a menu with options to add recipes, ingredients, steps, scale recipes, reset scale, clear recipes, and display recipes.

Menu Options
Add Recipe: Enter the name of the new recipe.
Add Ingredient: Enter the recipe name, ingredient details (name, quantity, unit, calories, food group).
Add Step: Enter the recipe name and the step description.
Display Recipes: Displays all recipes sorted alphabetically.
Display Recipe: Enter the recipe name to display its details, including ingredients, steps, total calories, and any calorie warnings.
Scale Recipe: Enter the recipe name and the scaling factor to adjust ingredient quantities.
Reset Scale: Enter the recipe name to reset its scaling factor to 1.
Clear Recipe: Enter the recipe name to remove it from the list.
Exit: Exit the application.
Unit Testing

Prerequisites
NUnit framework installed.
NUnit3TestAdapter installed for running tests in Visual Studio.
Running Tests
Navigate to the test project directory:


Adding recipes
Adding ingredients
Adding steps
Scaling recipes
Calculating total calories
Clearing recipes
The tests ensure that the application correctly manages recipes, calculates calories, and scales ingredients.

Conclusion

The RecipeManager application provides a comprehensive tool for managing and scaling recipes while keeping track of calorie information. The enhancements ensure a user-friendly experience and accurate calorie calculations with alerts for high-calorie recipes.
