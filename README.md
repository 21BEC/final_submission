#Create a Token

In this, we have to create a program that runs a contract in which we first store the values the user is storing can say Ether, and increasing it with the initial value that is 0, in a function named (mint) and in another function (burn) inside a contract we burn the values means the ether which is left after using and we do that by using conditional statement (if) like if the total cost is greater than the value can say then operate otherwise throw an error.

##Description

This contract is written on remix IDE in the Solidity programming language and the contract named MyToken is having 2 functions and both of them are public, 1 conditional statement, and a mapping. so first we store the details of our token like token Name, token Abbreviation, and totalSupply in which the token Name and token Abbreviation are in a string and supply is in an unsigned integer as the supply can be a negative no. we use mapping to store the data as a key and it can be any built-in data type I used address as a data type and the value of the data type can be any type I used an unsigned integer (uint) as mapping is used to connect unique Ethereum address to a specific value type. after that, I used a function named mint and passed 2 parameters address as _address and value as a _value which is (uint) corresponding to the key, and increased the total supply by that value. and increased the balance named as a fund by the value here value is the ether stored by a user/sender It will then add the value from the total supply and from the balance of the “sender”. And if the user/sender uses ether from the supply so has to be updated again like how much ether is left we use another function named (burn) and it will work just the opposite of the mint function It will deduct the value from the total supply and from the balance of the “sender”. to make sure that we use the if statement that the balance of the sender is greater than or equal to the amount that is to be burned.


##Contributing

Contributions to this repository are not accepted as it is for personal assignments. However, if you have suggestions or feedback, feel free to open an issue.

##License

This project is licensed under the MIT License. You are free to modify and distribute the code for personal and educational purposes.
