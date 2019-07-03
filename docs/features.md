# Features

Epirus provides an intuitive user experience, driven by the menu on the left-hand side of the screen. Clicking on the relevent menu item will take you to the associated page.

## Tokens

The tokens view provides a view of all tokens deployed in the network. Separate labels are given to
fungible or non-fungible tokens,  following the [ERC20](http://eips.ethereum.org/EIPS/eip-20) and [ERC721](http://eips.ethereum.org/EIPS/eip-721) Ethereum standards respectively.

![Tokens view](img/tokens.png)

When you click on one of your tokens, you get more information about it (as in the Contracts view). This includes details of all events that have taken place,  such as token transfers.

## Contracts

The contracts view displays all contracts that have been deployed to your network.

![Contracts view](img/contracts.png)

Contracts that comply with well-defined interfaces are immediately tagged with a type in the `Label` column to reflect this. For example, `ERC20` for fungible token contracts, `ERC721` for non-fungible token contracts, and Custom for those  not registered in the contract registry.

The `Name` column provides the contract name if the contract is registered in the Epirus contract registry. To learn more about the contract registry, head [here](metadata.md).

Clicking on a contract takes you to the contract details page. This is where you can find various information about the contract.

Here you can see details of all transactions associated with the contract and events emitted by these transactions. Contracts registered in the registry will have their events, parameter names and values decoded.

![Contract details view](img/contract_details.png)

Private transactions are labelled with a `Private` label. They will only be decipherable if the node that the Epirus instance is connected to is privy to the transaction.

## Transactions

![Transactions view](img/transactions.png)

The Transactions view provides details of individual transactions. This includes private transactions when supported by your blockchain.

![Transaction details](img/transaction_details.png)

When you vieiw a transaction's details you will be able to view lower-level details, such as the input byte code, which is available under the `Additional Details` menu.

![Input bytecode](img/input_bytecode.png)

## Blocks

![Blocks view](img/blocks.png)

The blocks view provides details of all blocks being generated on the network. As with the transactions view, technical details are available here too under the `Additional Details` menu.

![Block details](img/block_details.png)

## Accounts

If you click on an address that is not associated with a smart contract, i.e. it holds Ether, it will bring up the account view. Here you will find the current balance and transactions associated with the account.

![Account details](img/account_details.png)

## Search

The search box in the top-right corner of the screen allows you to search by various criteria, including:

- Contract address
- Account address
- Transaction hash
- Block hash

![Search box](img/search.png)

If a match is found, the associated contract, account, transaction or block details will be displayed.

## Advanced sorting and filters

Another key feature is the addition of sorting and filters in Epirus. This enables our users to 
find very active contracts by sorting their various views by key attributes. Contracts can be 
sorted by transaction date, transaction count or event contracts by transaction count.

![Filter by multiple attributes](img/filtering.png)

The filters provided also allow you to view subsets of the available data, such as only 
displaying contract creation transactions or fungible tokens in the Tokens view.

![Filter by token type](img/filtering_tokens.png)
