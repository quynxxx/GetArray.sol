# GetArray.sol
GetArray.sol
pragma solidity ^0.8.20;
contract GetArray {
    uint[] public arr;

    function push(uint x) public {
        arr.push(x);
    }

    function get(uint i) public view returns(uint) {
        return arr[i];
    }
}
