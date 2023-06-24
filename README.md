# final_submission

//overview of functions

The overview of the project is as :

In this contract, the constructor sets the initial values for the token name, abbreviation, and total supply. 
The fund mapping keeps track of the token balances for each address.

The mint function increases the total supply and adds tokens to the fund of the specified recipient.

The burn function deducts tokens from the total supply and the fund of the specified account. 
It includes a conditional if statement which ensures that the account has sufficient balance,
before burning the tokens.


// execution process

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.9" and then click on the "Compile final_assessment.sol" button.

Once the code is compiled, we can deploy the contract by clicking on "Deploy & Run Transactions".
After the contract is deployed, we will see the contract instance in the "Deployed Contracts" section below.

To interact with the contract, we can call the functions by entering the required parameters and clicking on the respective buttons (e.g., "mint" or "burn").
