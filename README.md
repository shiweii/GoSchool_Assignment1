# GoSchool_Assignment1
To develop a console application that would serve as a simple shopping list application to store the shopping list of the day.
## Application Feature
The shopping list application shall contain the following features.
  - View entire shopping list
  - Generate Shopping List Report
  - Add Item
  - Modify Items
  - Delete Item
  - Print Current Data
  - Add New Category Name
  - Modify Category Name
  - Delete Category
 
## Requirements
  - **View entire shopping list**
    - This feature shall display all available items in the shopping list.
  - **Generate Shopping List Report**
    - This feature shall generate the reports based on the available items stored at runtime.
      - Total cost of item by category
        - Calculate by the summation of all items of the same category.
        - Each item total cost is calculated by Item * Unit Cost.
      - List of items by category
        - Each item available will be “grouped” into the relevant
  - **Add Items information**
    - This feature adds information for the item of interest.
      - Name of the item
      - Category of the item
      - Unit Cost of the item
      - Quantity of the item
  - **Modify Existing Items**
    - This feature allows for the user to change the quantity of the item, regardless of the category.
  - **Delete Item from shopping list**
    - This feature deletes the item that is specified by the user.
    - If the item does not exist, the user is notified.
  - **Print current data fields**
    - This feature allows the display how the data is stored in the application.
    - If there is not data available, the user is notified.
  - **Add New Category Name**
    - This feature allows the user to add new categories to the existing categories.
    - If the category exists, the user is notified
    - If there is no input from the user, a “no input” is shown and the main menu is shown.
 
 ## Advanced Requirements
  - **Modify and delete category**
    - Modify category allows the user to modify the category of interest.
    - Delete category allows the user delete the category of interest.
    - This section is optional and open for each participant to design their own.
    - The design of the features should be logical. E.g. deletion of category would delete all stored category as well since it is no longer available.
    - Relevant warning should be given to the user as notifications. E.g. warning for nothing to modify or nothing to delete.
    - Deletion of category would reshuffle existing indexes of categories that are still available. E.g. deletion of Food at index 1 would make Drinks be reallocated as index 1.
  - **Storing of shopping lists and retrieving of lists**
    - Multiple shopping lists can be stored in a slice with allocated indexes using a “save shopping list" option.
    - User would be able to retrieve previous shopping indexes using a "retrieve previous shopping list" option and providing an index of interest.
    - The existing features should be able to access the retrieved shopping list.
