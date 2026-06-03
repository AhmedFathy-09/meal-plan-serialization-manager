# Meal Plan Serialization Manager

A basic Python program that lets you type in recipes and bundle them into organized meal plans. I built this project during my first year to practice creating custom Python objects and learning how to save information to text files.

## 🛠️ What I Practiced
* **Python Classes:** Built basic blueprints (`Recipe`, `MealPlan`, and `RecipeBook`) to keep recipe data organized in memory.
* **Reading & Writing Files:** Practiced opening text files (`.txt`), adding text to them, and reading them line-by-line so data isn't lost when the program closes.
* **Working with Strings:** Used standard Python string tools like `.split()` and `.join()` to unpack data separating it with slashes (`/`) and commas (`,`).

## 🚀 How the Program Works
1. **Asks for Input:** Prompts the user to type in a recipe name, ingredients, prep time, and total calories.
2. **Saves to Computer:** It automatically writes this text directly into a text file (`.txt`) on your machine.
3. **Searches Data:** Reads the text file back into memory and allows the user to look up a specific meal plan by its name.
