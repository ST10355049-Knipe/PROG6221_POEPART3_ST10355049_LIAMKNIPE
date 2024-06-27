# Recipe Management Application

## Description
This Recipe Management Application is a Windows Presentation Foundation (WPF) based desktop application designed to help users create, view, scale, and manage their recipes. It provides an intuitive interface for organizing culinary creations and experimenting with different variations.

## Features
- Add new recipes with ingredients and steps
- View existing recipes
- Scale recipes up or down
- Filter recipes by ingredient, food group, or calorie count
- Delete recipes
- Reset scaled recipes to original quantities

## Requirements
- Windows operating system
- .NET Framework 4.5 or higher

## Installation
1. Clone this repository or download the source code.
2. Open the solution in Visual Studio.
3. Build the solution to restore NuGet packages.
4. Run the application.

## Usage
1. Launch the application.
2. Use the main menu to navigate between different functions:
   - Add Recipe
   - View Recipe
   - Scale Recipe
   - Clear Recipe
   - Reset Scale

## Key Components
- `MainWindow.xaml`: The entry point of the application
- `MenuWindow.xaml`: The main menu interface
- `AddRecipeWindow.xaml`: Interface for adding new recipes
- `ViewRecipeWindow.xaml`: Interface for viewing and filtering recipes
- `ScaleRecipeWindow.xaml`: Interface for scaling recipes
- `DeleteRecipeWindow.xaml`: Interface for deleting recipes
- `ResetScaleWindow.xaml`: Interface for resetting scaled recipes
- `Recipe.cs`: Class representing a recipe
- `Ingredient.cs`: Class representing an ingredient
- `RecipeManager.cs`: Class managing the collection of recipes
