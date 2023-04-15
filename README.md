# BZRP
Coin in Base blockchain 

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.4;
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
contract bse is ERC20 {
    constructor() ERC20("BAZRP", "BZXR") {
        _mint(msg.sender, 1000000000 * 10 ** decimals());
    }
}


Error if decim > 10 WTF
