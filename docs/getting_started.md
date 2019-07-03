# Getting Started

Epirus supports many different hosting options, which all come with support from the Web3 Labs team:

1. You can find it in the [Azure Marketplace](https://web3labs.com/azure-offer) 
1. Alternatively, we provide a hosted or on-premise [Enterprise](#enterprise) version

There is also a basic [Free](#free) version.

This documentation details the features of our Azure and Enterprise versions.



## Azure

The [Azure Marketplace offer](https://web3labs.com/azure-offer) is the simplest full version of Epirus 
to get up and running with. It requires an active Azure cloud subscription.

![Azure Marketplace offer](img/azure_offer.png)

You will need to provide details of your managed ledger (or Ethereum/ Quorum) node. In your Azure portal, navigate to the Azure Blockchain Service instance you wish to use. From here click `Transaction nodes -> <your-transaction-node> -> Connection strings`

Then, copy the HTTPS access keys with node URL, such as `https://<your-service>.blockchain.azure.com:3200/<acess-key>`

You will be able to access the Explorer UI via `http://<instance-name>.<region>.cloudapp.azure.com`

To view the actual URL, navigate to the Overview page for the resource group you used for Epirus, then head to `Deployments -> blk-technologies.... -> Outputs -> epirusUrl`.

Please allow a few minutes for the service to fully initialise and display data when initially run. While it is loading, you will see the loading screen below.

![loading screen](img/loading.png)

Please note, it can take a several hours to display token and contract details as the entire blockchain history needs to be processed.


## Enterprise

Web3 Labs also provides hosted Blockchain Explorer instances. You can host these within your cloud subscription, or they can be hosted by us.

Some of the features include:

- SSO authentication (Active Directory, SAML, Okta, etc)
- Dedicated database
- Data encryption at rest and in transit
- Continuous backup and point in time data recovery
- Full access to backups
- Tableau integration support 

For further information please [email us](mailto:hi@web3labs.com). 


## Free 

A free, feature-limited version of Epirus is available [here](https://github.com/blk-io/epirus-free). This version is updated periodically. 

Our Azure and SaaS offerings are constantly updated to provide you with the latest features.
