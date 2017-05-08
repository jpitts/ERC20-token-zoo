# ERC20-token-zoo

Descriptions of various [ERC20](https://github.com/ethereum/EIPs/issues/20)-compatible Ethereum tokens, primarily focusing on examples for use in developing tokenized services. 

For tokens that are already deployed on the Ethereum network, use the [Etherscan Token List](https://etherscan.io/tokens).  

| Token | Author | Description | 
| ----- | ------ | ----------- |
| BAKT<br /> [o0ragman0o/Bakt](https://github.com/o0ragman0o/Bakt) | o0ragman0o | A payable and dividends-paying Ethereum contract in which ERC20 token holders elect a single holder as Trustee to manage the fund. |
| HumanStandardToken [ConsenSys/Tokens](https://github.com/ConsenSys/Tokens) | Simon de la Rouviere,<br /> ConsenSys | Standard token with some human-friendly additions. Initial finite supply (upon creation one specifies how much is minted). In the absence of a token registry: optional Decimal, Symbol & Name. Optional approveAndCall() functionality to notify a contract if an approval() has occurred. |
| ITT<br /> [o0ragman0o/ITT](https://github.com/o0ragman0o/ITT) | o0ragman0o  | Token with in-built currency exchange functionality. Includes exchange trading functions 'Buy', 'Sell', 'Cancel' and 'Withdraw' within the contract itself. The owner of the ITT can also set the trading state to live or halted. | 
| MiniMeToken<br /> [Giveth/minime](https://github.com/Giveth/minime) | Jordi Baylina,<br /> Griff Green,<br /> Giveth | Users can create a new clone token from any MiniMeToken with an initial distribution identical to the original token, at a specified block. Balance history is registered and available to be queried. The optional controller of the contract can generate/destroy/transfer tokens at its own discretion, and freeze transfers. |
| TST<br/>[uzyn/ERC20-TST](https://github.com/uzyn/ERC20-TST) | U-Zyn Chua | For testing of ERC-20 token apps. |
