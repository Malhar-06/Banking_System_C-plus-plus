# Banking_System_Cplusplus


Here is how the code works:

1. The `main` function creates a `Bank` object.
2. The user is prompted to enter their choice.
3. If the user chooses `1`, the `openAccount` method is called.
4. The `openAccount` method prompts the user to enter their name, mobile number, and PIN number.
5. A new `Account` object is created with the entered details and added to the `accounts` array.
6. The account number is displayed to the user.
7. The user is prompted to enter their choice again.
8. If the user chooses `2`, the `showAccountDetails` method is called.
9. The user is prompted to enter their account number and PIN number.
10. The `showAccountDetails` method searches for the `Account` object in the `accounts` array based on the account number.
11. If the account number is invalid, an error message is displayed.
12. If the account number is valid but the PIN number is invalid, an error message is displayed.
13. If the account number and PIN number are valid, the account details are displayed.
14. The user is prompted to enter their choice again.
15. If the user chooses `3`, the program exits.
16. If the user enters an invalid choice, an error message is displayed.

