# RestaurantsBillingSystem

This is a basic restaurants billing system in Assembly Language as part of my lab project.

It has a starter Starter Menu for Admin [Owner] and customer:

- Admin
- Customer
- Exit program

## Admin

He should `provide his password to continue`.
Old password is collected from a password file.

Once enters it has following Menu:

- To Print Sale
- To Change Password
- To Exit

### Print Sale

It prints the whole file of sales to show the owner.

### Change Password

It again asks for `old password` before asking `new password`. Once old password is checked then users enter the new password and it is stored in the password file. Then the program is moved to Main Menu.

## Customer

It's Starter Menu gives following options:

- To see Menu and Prices
- To see Deals and Offers
- To Place an Order
- To Reset the Bill [Cancel the order]
- To Exit [Terminate Program]

### Menu and Prices

It only prints the complete Menu with prices to help our customers in selection.

### Deals and Offers
<!-- TODO  -->

### Place an Order

It Places the order of customer by showing different dishes and their prices as follow:

- Oriental

  + Chicken Quorma
   + Pullao
   + Chicken Briyani
   + Chicken Karahi
   + Chicken Tikka
   + Murgh Haleem
   + Naan
   + Roti

- Chinese

   + Chicken Manchurian with rice
   + Egg Fried Rice
   + Chicken Macaroni
   + Chicken Shashlik

- Fast Food

   + Chicken Pizza
   + Zinger Burger
   + Chicken Shawarma
   + French Fries

- Dessert

   + Pineapple Cake
   + Chocolate Cake
   + Custard
   + Ice-cream 

- Drinks

   + Coca Cola
   + Sprite
   + Coca Cola [Regular]
   + Sprite [Regular]
   + Pineapple Juice
   + Mint Margarita
   + Coffee
   + Tea

After selecting the dish the program asks for quantity and generates a bill for customers.

### Reset the Bill [Cancel the order]

It clears the bill and cancel the whole order.
