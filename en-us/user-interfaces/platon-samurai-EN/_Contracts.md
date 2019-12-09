## What is wasm contract
Wasm contracts are applications built with webassebly. and deployed on PlatON. User can publish services directly by submitting code then deploying it via PlatON Samurai.


## How to deploy a wasm contract

1.On the [Contracts] page, click [Deploy Contract], as shown below:

![Image text](image/Contract_deploy.png)

2.The client switches to [Deploy Contract] page, select the sender (Execute From), set the [Contract Name] , import [Contract Bytecode] and [Contract ABI(Interface)], click [Deploy], as shown below:

![Image text](image/Contract_info_input.png)

3.A dialogue box will pop up as below, input the Executor’s [Wallet Password], click [Submit], and the contract starts to be deployed.

![Image text](image/Contract_creation_confirm.png)

**Note : Contract Bytecode**

*Wasm contract can be written with the contract development framework (reference [link to be confirmed]). After compiling, you can get a binary code file suffixed with .wasm, which is an executable instruction of the virtual machine, and the execution of the contract logic is completed by instruction sets on the virtual machine.*

**Note: Contract ABI (Interface)**

*After the contract being compiled, an ABI file suffixed with .json will also be generated. ABI is the abbreviation of Application Binary Interface, which can be understood as a contract interface description. after the contract being compiled, its corresponding ABI is also formed. ABI is somewhat similar to the interface definition in the program, describing the field name, field type, method name, parameter name, parameter type, method return value type etc.*

## How to add a contract that has been created 
After a contract being created by someone, you can add it to your client, the steps are as below.

1.On the [contracts] page, click [Add  Contract], as shown below:

![Image text](image/Add_contract.png)

2.The client switches to [Add Watch Contract] page, input [Contract Name], [Contract Address], [Contract ABI (Interface)], click [Add], as shown below:

![Image text](image/Add_contract_info.png)

3.Once completed, the newly added contract will be displayed on the home page of [Contracts]. 

**Note: Contract Interface & Address**

*You need to provide the contract interface and the contract address when Other users are adding contracts that you have deployed.  You can click the [Copy] button on the contract details page to get the contract address, click [interface] to copy and get the contract interface, and then send them to the users.*

As shown in the following figure:

![Image text](image/Address_abi.png)


## How to execute a wasm contract

1.On the home page of [Contract], select an existing contract, the client navigates to [Contract Information] page, as shown below:

![Image text](image/Contract_detail.png)

2.Select the function of contract to be executed, input relevant parameters, select the Execute Type（Ordinary Tx）and executor, click [Execute], as shown below:

![Image text](image/Execution_set.png)

3.The confirmation dialogue box pops up, input Executor’s [Wallet Password], the contract’s function start to be executed.

![Image text](image/Execute_Contract.png)

## What is privacy contract

The privacy contract is a special MPC contract on PlatON that leverages the PlatON platform's secure multi-party computing (MPC) capabilities to protect the privacy of calculated data. For more information please click [here](/en-us/development/[English]-PlatON-Privacy-Contract-Guide.md).

## How to deploy a privacy contract

The operation steps are the same as [How to deploy a contract](#How-to-execute-a-contract)

## How to execute a privacy contract

The operation steps are basically the same as [How to execute a contract ](#How-to-execute-a-contract), and slelect  [MPC Compute Tx] as the execution type when executing.

For more information about privacy contract, please click [here](/en-us/development/[English]-Deep-Understanding-Privacy-Contract-Dev.md).

