##Coffee Machine Program
Overview
This program simulates a coffee machine that can make espresso, latte, and cappuccino. It keeps track of the resources (water, milk, and coffee) and the profit generated from the sales of coffee. The user can interact with the machine by choosing a drink, inserting coins, and receiving change and their chosen coffee. The machine also provides a report of the remaining resources and profit upon request.

##Features
Make Coffee: Users can choose from three types of coffee: espresso, latte, and cappuccino.
Resource Management: The program checks if there are enough resources to make the chosen drink.
Coin Processing: Users can insert coins, and the program calculates the total amount.
Transaction Handling: The program checks if the inserted money is sufficient, provides change, and updates the profit.
Resource Deduction: After a successful transaction, the resources are deducted based on the chosen drink.
Report Generation: The machine can generate a report of the remaining resources and profit.
How to Use
Start the Machine: The program runs in a loop until the user decides to turn it off.
Choose a Drink: When prompted, enter espresso, latte, or cappuccino to order a drink.
Insert Coins: Follow the prompts to insert the required coins.
Receive Change and Coffee: If the transaction is successful, the program will provide change and the chosen drink.
Get a Report: Enter report to see the remaining resources and the profit.
Turn Off the Machine: Enter off to turn off the machine.
##How It Works
Resource Check: The function is_resource_sufficient checks if there are enough resources to make the chosen drink.
Coin Processing: The function process_coins handles coin input from the user and calculates the total amount inserted.
Transaction Handling: The function is_transaction_successful checks if the inserted money is enough for the drink and updates the profit.
Making Coffee: The function make_coffee deducts the required ingredients from the resources and serves the coffee.
Loop Control: The program runs in a loop, allowing multiple transactions until the user turns off the machine.
Notes
Make sure to enter the correct coin denominations.
The resources are limited; once they are depleted, the machine cannot make more coffee until it's refilled.
The program is designed to run in an environment where input can be provided directly by the user.
