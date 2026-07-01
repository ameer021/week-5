Week 5 Documentation

  1. Problem Analysis
    1.1 Problem Statement
      The café currently calculates customer bills manually. The objective is to create a Python program that automatically calculates the customer's bill based on the quantities of coffee, tea, and sandwiches         ordered and then prints a receipt.
    
  1.2 Inputs
    The program requires the following inputs:
      - Customer name
      - Coffee quantity
      - Tea quantity
      - Sandwich quantity
    
  Item prices:
    - Coffee = RM 8.50
    - Tea = RM 6.00
    - Sandwich = RM 12.00
  
  1.3 Outputs
    The program outputs:
      - Customer name
      - Coffee quantity
      - Tea quantity
      - Sandwich quantity
      - Total bill amount
  
  Example output:
  
  RECEIPT 
      Customer : Bobby
      Coffee   : 3
      Tea      : 3
      Sandwich : 2
      -------------------
      Total = RM 67.50
  
  
  1.4 Typical Process Flow
    1. Start the program.
    2. Ask the user for the customer name.
    3. Ask for the quantity of coffee ordered.
    4. Ask for the quantity of tea ordered.
    5. Ask for the quantity of sandwiches ordered.
    6. Calculate the total bill.
    7. Print the receipt.
    8. End the program.
  
  1.5 Constraints
    - Quantities cannot be negative.
    - Quantities must be integers.
    - Only coffee, tea, and sandwiches are available.
    - Prices are fixed.
    
  
  2. Problem Decomposition
      The problem can be divided into smaller tasks:
        Task 1: Input Collection
          - Get customer name.
          - Get quantities for coffee, tea, and sandwiches.
          
        Task 2: Calculation
          - Calculate coffee cost.
          - Calculate tea cost.
          - Calculate sandwich cost.
          - Calculate total bill.
        
        Task 3: Output
          - Print customer details.
          - Print quantities ordered.
          - Print the total amount.
  
  3. Pseudocode
     
  START
  
   SET coffee_price = 8.50
    SET tea_price = 6.00
    SET sandwich_price = 12.00
    
   INPUT customer_name
    INPUT coffee_quantity
    INPUT tea_quantity
    INPUT sandwich_quantity
    
   total = (coffee_quantity * coffee_price) +
            (tea_quantity * tea_price) +
            (sandwich_quantity * sandwich_price)
    
  DISPLAY receipt
  DISPLAY customer_name
  DISPLAY coffee_quantity
  DISPLAY tea_quantity
  DISPLAY sandwich_quantity
  DISPLAY total
  
