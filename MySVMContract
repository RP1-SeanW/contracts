// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract MySVMContract {
    string public message;

    constructor(string memory _message) {
        require(bytes(_message).length > 0, "Message cannot be empty");
        message = _message;
    }
}
