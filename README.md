# eth11
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract Donation {
    uint256 public totalDonations;

    function donate() public payable {
        totalDonations += msg.value;
    }
}
