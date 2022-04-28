# Commercial Bank Joint Accounts
___________
A Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.
___________

## Smart Contract Life Cycle:

* Define the business scenario where we want to use a smart contract.

* Architect the functionality of the smart contract, and define the functions.

* Create the code that implements the solution that we want to build.

* Compile the smart contract in the Remix IDE. If any errors occur, fix them.

* Deploy the smart contract in the Ethereum network.

## Instructions:

1. Create a Joint Savings Account Contract in Solidity: [Remix Web IDE](https://remix.ethereum.org/)

2. Compile and Deploy Your Contract in the JavaScript VM: `joint_savings.sol`

<p style="text-align:center;"><img src="./Execution_Results/Deployment_Verification.png" width="500" height="200"/></p>

3. Interact with Your Deployed Smart Contract:

* Use the `setAccounts` function to define the authorized Ethereum address that will be able to withdraw funds from the contract.
<p style="text-align:center;"><img src="./Execution_Results/set_reciever_accounts.png" width="500" height="200"/></p>

* Deposit 1ETH:
<p style="text-align:center;"><img src="./Execution_Results/1ETH.png" width="500" height="200"/></p>

* Deposit 5ETH:
<p style="text-align:center;"><img src="./Execution_Results/5ETH.png" width="500" height="200"/></p>

* Deposit 10ETH:
<p style="text-align:center;"><img src="./Execution_Results/10ETH.png" width="500" height="200"/></p>

* Withdraw into AccountOne 5ETH:
<p style="text-align:center;"><img src="./Execution_Results/AccOne_withdraw_5ETH.png" width="500" height="200"/></p>

* Withdraw into AccountTwo 10ETH:
<p style="text-align:center;"><img src="./Execution_Results/AccTwo_withdraw_10ETH.png" width="500" height="200"/></p>
