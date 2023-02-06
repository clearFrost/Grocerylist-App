# UserManual

**Authors**: Andrew Zheng, Tao Hu, Jason Kang, Parabjot Chander, Konrad Rakowski (Team 4)

## How to Navigate Our App

### 1. Log In Page

- When the user opens up our app, they will be greeted with the **login interface**, which requires them to enter the 
correct username and password to procede into the next activity. 

- The account stored in our application has the credentials of **Username: admin** and **Password: admin**.

- A successful toast message will be shown if you entered the correct credentials into the textboxes, however, an
error toast message would pop up if any incorrect information is entered.

- If the user were to click the **forgot password?** button, a toast message will be shown saying that the username and password is **admin**.

### 2. Grocery List Management Interface

After a successful login, the user will move on to the **grocery list management interface**, in which a grocery list is
able to be created.

#### 2.1 Creating a Grocery List

- On the bottom of the screen, there is a **Create Grocery List** button, where it prompts the user to enter a name for the 
new list. 

- If the user does not enter any values/strings into the textbox, it will send a toast message to the user saying 
"invalid name".

- There is a **cancel button** for the user that goes back to the interface if they decide not to create a new grocery list.

- The newly created grocery list will appear in the interface after the user inputs a string into the texbox and finalizes 
it by pressing **Create List**.


#### 2.2 Renaming a Grocery List

- After the user creates a list, the user has the ability to rename one of their already available grocery lists by pressing
the **rename button**. 

- When clicked, the user is brought to a menu similar to **Create Grocery List** and is asked to enter a new name for their
selected list. 

- Similarly to **Create Grocery List**, if the user does not enter a valid value/string, the app will send a toast to try again with a different input.


#### 2.3 Deleting a Grocery List

- Under the **rename button** we have the **delete button**, which allows for the user to delete the lists that they have 
created.

- Upon clicking the **delete button**, the user must confirm whether they really want to delete their grocery list or not, where they have the option to cancel if their mind was changed.

- If the **delete** option was clicked, the list is deleted from **grocery list management** and cannot be seen again.


#### 2.4 Selecting a Grocery List

- After the user has created their grocery list, they have the option to select a list of choice to explore the other
functionalities the application has to offer.

- The user can **select** a list by clicking on the name of said list.



### 3. Grocery List Items

After a successful selection of a grocery list, the user will be brought to the **Grocery List Items** activity, where
there are various options the user can choose to modify the contents of their grocery list. 


#### 3.1 Clear All Checks

- The user are able to check their list of items in the grocery list. But upon clicking the **clear all checks** button, the items found in the user's grocery list will be market unchecked.


#### 3.2 Adding an Item

- Upon clicking the **adding an item** button, the user will be brought to another page in the application, greeted with a search bar that can search for an item based on how similar the input was, i.e.(a -> apples).

- After conducting their search, the user is able to choose an item that was brought up via searching and add it into the grocery list by clicking **add item**.

- When the **add item** button is pressed, the user will then have to input the quanity of the item they selected, as well as the units for said item, i.e.(2 pounds).

- When the user tries to add an item into the list that is not found in the database, they are redirected into the **other options** page, where they can manually add their new item into the database.


#### 3.3 Browse Items

- Upon clicking the **browse items** button, the user will be brought to another page in the application, showing a list of
every item behind its item type in the database.

- The user is able to look for any item in this **browse items** section and add it into their own grocery list.


#### 3.4 Other Options

- Upon clicking the **other options** button, the user will be brought to another page in the application, greeted with a series of input text boxes to 
add a new item into the list, as well as into the database.

- To add an item into the grocery list, the user must enter the **listId**, **itemId**, **itemName**, **itemType**, **itemQuantity**, and **itemQuantityType** into their respective fields.

- If any fields are to have incorrect information, the application sends a toast message that there was an error in adding your item.

- If the user wants to delete an item from the list, they only need to enter the **listId**, **itemId**, and **itemName** to do so.

- If the user wants to manually add an new item into the database, they would have to input an **itemID** and **itemName** into the two text boxes below. The added item will appear within the search bar in **adding an item** menu.

- For a new itemType, the user must input their type into the **itemType** text boxes and it will be visible in the **browse items** page.

#### 3.5 Deleting/Edit Quantity and Unit 
- After the user added their desired item, the user are given the option to delete items or edit the item by their quantity/unit. Similar to the Grocery List Management Interface, these buttons will be visible next to each grocery items. Upon clicking these buttons, an dialog will appear prompting the user with the choice to continue deleting/editing the item or cancel the option.


## Future App Functionalities

- Logout Feature for the user where the user can logout in the 2 interfaces (Grocery list(s) management and Selecting a list Interface).

- Creating an account in the login interface for the new customers. 

- Attaching prices to each grocery items.

- Adding an checkout feature that calculate the sum of the grocery items.

## Note:This app is targeted for 31 API, but it should be runnable at all/most API levels.


