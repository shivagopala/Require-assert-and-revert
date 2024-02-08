# RiverFlow Smart Contract

## Overview

The RiverFlow smart contract is designed to simulate the challenge of swimming across a river from Point A to Point B. The contract includes functions to check if a swimmer can reach Point B and if they can make a round trip with a speed boost.

##  Contract Details

#### Constants

- `riverSpeed`: A constant representing the speed of the river in Km/hr (set to 10).

#### Functions

1. **`Destination_A(uint256 swimmerSpeed, uint256 timeTaken) external pure`**
    - Check if the swimmer's speed is greater than the river speed.
    - Check if the time taken is less than 20 hours.

2. **`BoostSpeed(uint256 boostAmount) external pure`**
    - Use an if statement to check if the boost amount is more than 5 km/hr.
    - Revert with an error message if the boost allows the swimmer to make a round trip

## License

This smart contract is released under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Tejaswi

shivagopala70@gmail.com
