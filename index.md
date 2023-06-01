//Unit Test


1.
- The function is multiplication, it returns the product of two input numbers

expect multiply(1, 3) to be 3
expect multiply(5, 4) to be 20
expect multiply(6, 6) to be 36
expect multiply("8", 9) to be an error
expect multiply(-4, 10) to be -40

2.
- A function called "concatOdds" takes two arrays of integers as arguments. 
- It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays

expect concatOdds([1, 3, 4, 9], [7, 13, 16, 20]) to be [1, 3, 7, 9, 13]
expect concatOdds (1) to be an error
expect concatOdds (["3, 5, 6, 8"], [15, 19, 25, 27]) to be an error




Functional Test
Customer uses a shopping cart checkout feature that allows to check out as a guest or as a user
1. Asking if they want to create and account or log in if they check out as a guest
2. Users with a logged in account can add items
3. Users that check out as a guest can add items
4. The user can see a checkout page when they press checkout
5. If the cart is empty it should indicate to the user that the cart is empty
6. If the user is logged in they can view cart and checkout
7. Guests that checkout won't have the same features as registered users do
8. Logged in users can take advantage of promos that unregistered users cannot
