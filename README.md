# EvenOddChecker.sol
luonganhtuan2
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract EvenOddChecker {
    function isEven(uint256 number) public pure returns (bool) {
        return number % 2 == 0;
    }
}
