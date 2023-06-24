# final_submission

The overview of the project is as :

In this contract, the constructor sets the initial values for the token name, abbreviation, and total supply. 
The fund mapping keeps track of the token balances for each address.

The mint function increases the total supply and adds tokens to the fund of the specified recipient.

The burn function deducts tokens from the total supply and the fund of the specified account. 
It includes a conditional if statement which ensures that the account has sufficient balance,
before burning the tokens.
