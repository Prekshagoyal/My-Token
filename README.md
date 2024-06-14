# MyFirstToken
Sample code repository showcasing token creation, a secure method of authentication for systems and APIs. This code demonstrates best practices and provides a starting point for developers implementing token-based authentication in their applications.
## Description
Token creation involves developing a digital asset on a blockchain network using mapping to define three public variables: token name, abbreviation (abbrev.), and total supply. Mapping allows efficient access and retrieval of information. These variables represent the token's name, abbreviation, and maximum supply. This approach provides transparency and flexibility for managing the token within the blockchain ecosystem.
## Getting Started
### Executing Program
The token creation contract incorporates three essential public variables: tokenName, tokenAbbrv, and totalSupply. These variables serve specific purposes within the contract's functionality. 
* The tokenName variable is of string data type and denotes the name assigned to the token. 
* Similarly, the tokenAbbrv variable, also of string data type, represents the abbreviation associated with the token. 
* Lastly, the totalSupply variable, an unsigned integer, signifies the overall supply of tokens available.

These public variables play a crucial role in defining and identifying the token within the contract, enabling effective management and interaction with the token throughout its lifecycle.

The contract's mapping, balances, enables efficient storage and retrieval of token balances for addresses, ensuring seamless tracking of ownership and facilitating secure transactions within the blockchain ecosystem.

* Token Creation:
The contract includes a "mint" function that increases the total supply by a specified value and augments the balance of a given address accordingly. This facilitates the creation of new tokens while accurately tracking the total supply and individual balances.

* Token Destruction:
For token destruction, the contract features a "burn" function that deducts a specified value from both the total supply and the balance associated with a given address. This controlled reduction in supply and balance allows for the removal of tokens while maintaining accurate records within the contract.

## License

This project is licensed under the MIT License - see the LICENSE.md file for detail
