# Activity: Shopping List
## Goal
- Create a small webpage where the user can:
- Type an item.
- Click Add Item.
- Store the item in an array.
- Show all items on the page.
- Show the total number of items.

### What Learners Must Understand
1. Array
let items = [];
This creates an empty array.
2. Get the Input Value
const newItem = input.value;
This gets what the user typed.
3. Add to the Array
items.push(newItem);
push() adds the new item to the array.
Example:
["Bread", "Milk", "Eggs"]
4. Loop Through the Array
items.forEach(function (item) {
forEach() goes through every item in the array.
5. Create an HTML Element
const li = document.createElement("li");
This creates a new list item.
6. Add Text
li.textContent = item;
This puts the item name inside the <li>.
7. Add It to the Page
itemList.appendChild(li);
This displays the item on the webpage.
8. Count the Items
items.length
This tells us how many items are inside the array.

**Example**
The user enters:
Bread
Then:
Milk
The webpage shows:
Shopping List

Bread
Milk

Total items: 2

Simple Challenge
Add a Remove Last Item button.
Hint:
items.pop();
pop() removes the last item from the array.
