Star_Token
This solidity program "StarToken" is a simple program which imitates the token creation (minting and burning coins) process on my local Blockchain

Description
The program consists of:

3 public state variables which will provide the token name, token abbreviation and total supply for my token.
Minting function "mintToke()" which will take address and value as parameters and then it increases the total supply by that number and increases the balance of the address by that amount.
Burn function "burnToken()" which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
This burn function will also check the amount to be burned must be less than or equal to the balance present in that address
