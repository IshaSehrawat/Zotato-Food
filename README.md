# Zotato-Food
This application primarily is a platform for restaurants and diners to connect facilitated by food delivery executives.
Customers are generally charged 40/- delivery charge per order. There are additionally, two special categories:
    ● Elite Customers - Free delivery (50/- off on bill value greater than 200/- after restaurant discount)
    ● Special Customers - 20/- delivery charge per order (25/- off on bill value greater than 200/- after restaurant discount)
Restaurants do not generally have overall bill discounts. However there are additionally,two special categories.
    ○ Fast food - Has an option to discount overall bill value
    ○ Authentic restaurants - Has the option to discount overall bill value + 50/- off on all orders (if bill is greater than 100/- after overall bill value discount)
Each food item can have their own individual discounts.
Owners must add categories to each food item so that customers can have clarity. The categories consist of : "Starter", "Main Course", "Dessert", "Beverage".
Restaurants need to pay 1% of the total bill value (after discounts) to the food tech company (Assume Restaurants have surplus money to pay).
There is a reward scheme for customers as follows -
    ○ Fast food - 10 points per 150/- spent
    ○ Authentic restaurants - 25 points per 200/- spent
    ○ Rest - 5 points per 100/- spent
    (All the above rewards are applicable on total order value after all discounts, 1 point = 1 rupee)
A customer may add food items from only one restaurant in a single order.
The application has a parent menu to navigate all functionalities. The first two menu options pertain to restaurant owner login and customer login.
Option 3 displays user details of selected restaurant or customer details. (Given option to choose between the two and the subsequent User)
    a. Customer - Name (Category, if any), address, account balance
    b. Restaurant - Name, address, number of orders taken
Option 4 - Print details of total charges collected from restaurants (as transaction fee) and delivery charges from customers
Option 5 - Exit the application
Restaurant queries -
      1) Add food items - To add item details - ID (generated by application), Name, price, quantity, discounts if any, Print their details
      2) Edit food items - Modify any of the above-mentioned item details - Name, price, quantity, discounts
      3) Print rewards - To print the number of reward points claimed by customers
      4) Discount overall bill value - Applicable for Authentic and fast-food restaurants (Input is taken as integer, which is percentage discount, say 1 means 1% discount)
      5) Exit
Customer queries -
      1) Selecting
      2) Checkout
      3) Reward
      4) Cart History
      5) Exit
