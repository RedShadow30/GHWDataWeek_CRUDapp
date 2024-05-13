# GHWDataWeek_CRUDapp

Application needs:
- Meal Plan
    Different receipes we want to cook throughout the week, month, year, etc
    Add/update/delete meal
    Meal id: Recipe name
    Serving size: Number of people the receipe feeds
    Carbs (g)
    Protein (g)
    Ingredients: Dictionary
    Recipe: Text/link to website of a recipe

- Schedule Plan
    Our plans throughout the next week, month, year, etc.
    Can integrate entire schedule - integrating any plans you have that will affect your eating for next week
    eating_location: ['at home', 'not at home']
    add/update/delete our plans
    plan_id: what the plan is ['work lunch', "dinner at mom's house", "party at john's", "movie night with roomate"]
    date: month/day/year
    time: hour:minute or ['breakfast', 'lunch', 'dinner']
  
 - Grocery List
    What foods we need to buy for our meal plan
    Based off of the meals in the next 2 weeks
    Able to add/update/delete individual items if you need more seasoning or already have some food at hom
    count: number of grocery items needed (integer)
    grocery_id: name of the grocery store (text)
