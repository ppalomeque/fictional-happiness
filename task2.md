# Task 2
1. `CookBook` goes beyond CRUD. The listed functions can fit under:
    - **Create**: post recipies
    - **Read**: view and search recepies
    - **Update**: update recipies
    - **Delete**: remove recipies
    However, query and search capability are not technically part of CRUD, and so the app goes beyond CRUD.
2. 
- We can add a recommendations feature where recepies with similar attributes as the user's previously viewed recepies. These attributes can include culture (Italian, Mexican), ingredients (chicken, tomatoes, spinach), and prep time.
- We can add a recipe scaling feature that changes the amount of people the recipe serves and adjusts the ingredients accordingly, which introduces domain-specific calculation.
3.
- We can have an "ingredient-first" approach to recpies, where the user enters the ingredients he has, and `CookBook` returns recipes, ranked by how many of the ingredients are present.
- We can have a feature where the app adapts the recipe from constraints, such as without specific ingredients, or with extra of another ingredient.