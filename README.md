# Recipe Finder Using API  
### Ingredient-Based Recipe Suggestion System

This project is a Python-based Recipe Finder application that allows users to search for recipes using a single ingredient such as potato, rice, or mushroom. The system first attempts to fetch recipe data from an online API (TheMealDB). If the internet is not available or the API does not return results, the program automatically switches to offline mode and uses a preloaded dataset of vegetarian-style recipes.

## Features
- Search recipes using a single ingredient  
- Online API support (TheMealDB)  
- Automatic offline fallback with 30 stored recipes  
- Displays clean recipe details: ingredients, category, area, instructions  
- Save any recipe to a text file  
- Works even without internet  
- Simple and user-friendly system  

## Technologies Used
- Python  
- API GET Method  
- JSON Parsing  
- Object-Oriented Programming (OOP)  
- File Handling  
- Requests Library  


## How It Works
1. User enters an ingredient name  
2. System first tries to fetch recipes from the online API  
3. If online results are not available → offline recipe database is used  
4. Matching recipes are displayed  
5. User selects one recipe to view complete details  
6. User can save the recipe into a `.txt` file  

## API Used
Filter recipes by ingredient:  
`https://www.themealdb.com/api/json/v1/1/filter.php?i=IngredientName`

Get full details of any recipe:  
`https://www.themealdb.com/api/json/v1/1/lookup.php?i=MealID`

## Example Input/Output
### User Input:

### System Output:
- Shows all potato-based dishes  
- Displays full recipe details (ingredients + instructions)  
- Option to save recipe to text file  

## Future Enhancements
- Add recipe images  
- Create full GUI using Tkinter or PyQt  
- Add voice input  
- Convert into Android or Web app  
- Add nutrition and calorie details  

## Author
**Juber Nayta**  
Recipe Finder Using API – Python Project  

## License
This project is open-source and free to use.
