# Module_3_Challenge

Customer Banking Application

Overview
  
  This Python project is designed to manage savings and CD accounts, consisting of four key modules:

  Accounts.py: Defines the Account class, responsible for handling account details such as balance and interest.

  savings_account.py: Implements the functionality specific to savings accounts. It calculates interest and updates the account balance.

  cd_account.py: Implements the functionality specific to CD accounts. It calculates interest and updates the account balance.

  customer_banking.py: Orchestrates the main functionality by interacting with the user, utilizing the savings and CD account modules, and displaying results.

How Modules Work Together

Initialization with Account Class:
 
  Both savings_account.py and cd_account.py create instances of the Account class, initializing fundamental attributes such as balance, interest, and months.
  Utilization of Specific Account Functionalities:

  savings_account.py and cd_account.py utilize the shared Account class methods to set balances and interests specific to their account types.

Orchestrated User Interaction in customer_banking.py:

  customer_banking.py orchestrates user interactions, prompting for user inputs, and calling functions from savings_account.py and cd_account.py to perform necessary calculations.

Display of Results:

  The results, including interest earned and updated balances for both savings and CD accounts, are then displayed to the user.
