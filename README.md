# Solidity

![blockchain_image](./Images/blockchain_image.jpg)




Three different smart contracts were deployed to the Ropsten Test Network that were created to automate a company's finances.  Included in this repo is the .sol files for each smart conttract.  The addresses for each contract are provided below.

### Associate Profit Splitter Contract

The address for this contract is 0xf5367f97e6885d7059e92205e34d9d39275770dd on the Ropsten Test Network.  This contract will accept Ether and divide the Ether evenly amongst the associate level employees allowing for payments quickly and efficiently.  Testing for this contract was done using the Ganache development chain.


### Tiered Profit Splitter Contract

The address for this contract is 0x6bee3e882f9bfce5bf7c46430bc80c70c53a0829 on the Ropsten Test Network.  This contract adds a level of complexity to the previous contract by allowing the profits to be split up between different levels of employees besides just associate level.  There is a set percentage for different tiers of employees.  Testing for this contract was done using the Ganache development chain.


### Deferred Equity Plan Contract

The address for this contrat is 0x674e722e95d224721087db9423170f78d463bd78 on the Ropsten Test Network.  This contract manages an employees deferred equity incentive plan in which 1000 shares will be distributed over 4 years to the employee.  The amount of shares distributed is based per year is 500 shares annually for the 4 year vesting period.  Testing for this contract was done using the Ganache development chain.