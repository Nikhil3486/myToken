Tokens:-

In this we are creating our own tokens.

Description:-

Basically a token is being created using solidity language and some functions are used like minting and burning.
your contract should fulfill following conditions:

1.Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply).

2.Your contract will have a mapping of addresses to balances (address => uint). 

3.You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.

4.Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.

5.Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

Getting Started:-

Installing

open gitpod and create your account.

No modifications needed to be made to files/folders


Executing program

simply copy and paste on your gitpod and run the program.

Authors:-

NIKHIL CHANDEL
https://www.linkedin.com/in/nikhil-chandel-86b4b722a/

License:-

This project is licensed under the MIT License - see the LICENSE.md file for details
