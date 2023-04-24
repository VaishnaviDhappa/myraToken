# MyToken Solidity Contract
MyToken is a simple ERC-20 token contract written in Solidity programming language. This contract defines a token named ETHPriya with an abbreviation of EP and a totalSupply of 0. The contract allows users to mint and burn tokens.

# Getting Started
To use this contract, you will need to have a working environment for Solidity. You can use Remix or any other development environment that supports Solidity.

# Usage
This contract has two functions: mint and burn.

# mint function
The mint function is used to add tokens to an address. The function takes two parameters: _address, which is the address to receive the tokens, and _value, which is the number of tokens to mint.

```solidity
function mint(address _address, uint _value) public {
    totalSupply += _value;
    balances[_address] += _value;
}
```

# burn function
The burn function is used to remove tokens from an address. The function takes two parameters: _address, which is the address to burn the tokens from, and _value, which is the number of tokens to burn.

```solidity
function burn(address _address, uint _value) public {
        totalSupply -= _value;
        balances[_address] -= _value;
    }
```

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Contributing
Contributions are welcome! If you find any issues or want to add new features, please create a pull request.

# Acknowledgments
This contract was created as a learning exercise for Solidity programming language. Thanks to the Ethereum community for their excellent documentation and resources.




