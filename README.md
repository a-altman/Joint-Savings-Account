# Joint-Savings-Account

Open or copy code found in joint_savings.sol to and IDE such as remix.ethereum.org.
See images in Execution_Results for examples of what it should look like when you successfully interact with this smart contract. 

To interact with this deployed smart contract, complete the following steps:


1. Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

- Note You can either use the following Ethereum addresses or create new, dummy addresses on the Vanity-ETH website, which includes an Ethereum vanity address generator.

- Dummy account1 address: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
- Dummy account2 address: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0



2. Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the contractBalance function to verify that the funds were added to your contract:


Transaction 1: Send 1 ether as wei.
- see item 0 in Execution_Results

Transaction 2: Send 10 ether as wei.
- see item 1 in Execution_Results

Transaction 3: Send 5 ether.
- see item 2 in Execution_Results


- Note Remembering how to convert ether to wei and vice versa can be challenging. So, you can use a website like Ethereum Unit Converter to ease doing the conversion.



3. Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the contractBalance function to verify that the funds were withdrawn from your contract. Also, use the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.
- see items 3 - 8 in Execution_Results