# VendingMachine

The solution is build using .NET Core 3.1

# Libraries used:
- FluentValidation - it is used for user input validations.
- Autofac - it is used for DI
- CommandLineParser - it is used for parsing console arguments.
- MediatR - it is used to build CQRS

# Patterns
 - CQRS, 
 - State


Vending machine should support the following features:
• Accept coins - Customer should be able to insert coins to the vending
machine.
• Return coins - Customer should be able to take the back the inserted coins
in case customer decides to cancel his purchase.
• Sell a product -Customer should be able to buy a product.
• If the product price is less than the deposited amount, the Vending machine
should show a “Thank you” message and return the difference between the
inserted amount and the price using the smallest number of coins possible.
If the product price is higher than the amount inserted, Vending machine
should show a message “Insufficient amount”
• The amount and type of coins returned should be shown by the UI.
                          
 
 
