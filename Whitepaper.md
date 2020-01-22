![alt text](https://github.com/mootz12/OptionBlox/blob/master/photos/obx%20logo.png "Logo Title Text 1")
# OPTIONBLOX
## A Derivatives Writing and Trading Solution Built on Stellar

Markus Paulson-Luna: markuspaulsonluna@gmail.com  
Andrew Pierskalla: piers274@gmail.com  
Alexander Mootz: alexjmootz@gmail.com  

### Abstract

Adventum Technology presents a decentralized system for writing and trading financial derivatives. We showcase OptionBlox, a tool that can be used to drastically decrease market friction and costs through reduced back-office requirements and regulatory restrictions. OptionBlox enables any individual to write and trade any derivative and creates opportunities for new derivatives and derivative markets. It uses a unique smart contract structure which allows for trust-free option, future, and forward writing. Using OptionBlox, a market participant can buy and sell these derivatives on a decentralized exchange. We also enable users to exercise these derivatives with no risk to any party. In addition, OptionBlox presents a unique ledger-based margin account framework. We allow organizations building exchanges on Stellar to provide their users with decentralized margin accounts that minimize default risk. Finally, we will discuss security measures that prevent the abuse of these less-regulated assets.

### Introduction:

#### Derivatives:

A derivative is a contract between two parties. Its value is based on an agreed-upon asset or a set of assets. The most common forms of financial derivatives are futures, options, and forwards.
 
- Futures are a contract between two parties to buy/sell an agreed-upon quantity of an asset at a set price at an established future time. These are most commonly used to hedge against price movement by the underlying asset, a means to increase leverage or a means of gaining exposure to rates. Futures are typically settled daily, so at the end of the day, an investor is liable for however much they have gained or lost.
 
- Options are contracts between two parties, a writer and a buyer. They give the buyer the option, but not the obligation, to buy or sell an asset at an agreed-upon price until the option expires. If the buyer decides to exercise this right, the option writer would be the seller or buyer respectively. Options can be either American or European style and can be either puts or calls. American style options can be exercised at any date up until their expiration date. European style options can only be exercised on their expiration date. A call option allows the buyer to purchase the underlying asset at the agreed-upon strike price, and a put option allows the buyer to sell the underlying asset at the strike price. Common uses of options are hedging, increasing leverage, and income generation.
 
- Forwards are similar to futures. The main difference is that they are not settled until the expiration date. They are typically highly specified to the buyer and seller's needs.

#### Value Proposition:  

- *Decreased Costs*  
The incumbent derivatives market comes with a large amount of friction. It requires middlemen to provide access to the market, facilitate trades, and lower counterparty risk. This inefficiency creates costs that get passed on to investors. CBOE, one of the largest derivative exchanges, had revenues of $0.480 per option contract traded and $2.513 per future contract traded [(source)](http://ir.cboe.com/~/media/Files/C/CBOE-IR-V2/documents/annual-proxy/2017-annual-report-and-form-10-k.pdf). This is all added cost for investors. Using our system, processing both types of contracts costs around one-thousandth of a cent. These savings become exponentially larger when you consider OTC (over-the-counter) derivatives. These contracts are highly specific, complicated, and can carry a large amount of counterparty risk. Our system makes it significantly easier to create and trade OTC derivatives, while also greatly lowering counterparty risk. These improvements make OTC derivatives much cheaper and more accessible. 

- *Market Accessibility*  
OptionBlox increases market accessibility. Investors around the world struggle to participate in major derivative markets unless they live in developed nations. The decentralized nature of our system means our service is accessible to anyone with an internet connection. It also does not fall under any national regulatory body's jurisdiction. As a result, millions of investors gain efficient access to major derivative markets. 

- *Market Flexibility*  
Stellar's Anchor system combined with the flexibility of OptionBlox means our platform allows users to write derivatives with any asset. People with needs for derivatives that are not currently supported by the traditional market can write and trade derivatives that better suit their requirements.  

#### What Decentralization Provides:

Decentralizing our service allows us to make it more flexible and efficient than the incumbent system, while still retaining a similar level of security. The elements of a decentralized system that are most important to us are:
 
- *Proof of ownership*  
The public and collective nature of a decentralized ledger means individuals can't misrepresent what they own on the ledger, including assets and smart contracts. This allows us to easily verify asset ownership and ensure smart contracts are set up correctly. The result is that the consumer's need for middlemen to handle counterparty risk is greatly reduced.

- *Accessibility*   
Decentralized networks are incredibly accessible. They are run by a network of nodes situated around the globe, and any individual can connect to the network or become one of the nodes. On top of this, Stellar has an exchange functionality built into its network. The open nature of this system means that consumers no longer require a third party to host an electronic exchange and provide them access to it. Additionally, it opens the market to new parties that find it difficult to access incumbent markets. Finally, the lack of reliance on third parties to provide market access combined with the flexibility of our derivative writing protocol allows consumers to write new kinds of derivatives, potentially creating new markets.

- *One source of truth*  
The unquestionable nature of a decentralized network combined with its accessibility means that participants don't need to pay for or share market data to maintain an accurate source of information. This cuts out another source of friction and cost.

#### Our Decentralized Ledger:

We use Stellar's decentralized ledger to support our protocol.   
In Stellar’s words:  
“Fundamentally, Stellar is a system for tracking ownership. It uses an accounting ledger, shared across a network of independent computers, to store two important things for every account holder: what they own (their account balances) and what they want to do with what they own (operations on those balances, like buy or sell offers.)

The computers that run Stellar and publish the ledger are called nodes. They systematically validate the ledger’s contents so it’s always consistent across the network. For example, when you send someone a dollar on a Stellar-built app, the nodes check that the correct balances were debited and credited, and each node makes sure every other node sees and agrees to the transaction.”

Stellar's open network allows anyone to submit a transaction to change the ledger. However, the transaction will only change the ledger after the nodes agree it is valid. In our case, before a derivative is exercised or traded, the local network of nodes agree upon the validity of the transaction. This prevents parties with ill intentions from engaging in illicit behavior on the network. Therefore, we have a secure financial network that has one source of truth and can be instantly accessed and modified by anyone in the world.  

For more general information visit: [Stellar's website](https://www.stellar.org/developers/guides/walkthroughs/stellar-smart-contracts.html).  
For more information on how the nodes validate transactions see: [Stellar Consensus Protocol](https://www.stellar.org/developers/guides/concepts/scp.html).  
For more information on how we interact with Stellar’s network visit: [Network Overview](https://www.stellar.org/developers/guides/get-started/index.html).

Terms:
Smart Contract: A protocol to digitally facilitate, verify, or enforce the performance of a contract.  
Keypair: When an account is created on Stellar's ledger, they are assigned a public and a private key. The private key is used to sign transactions and the public key is used to identify the account. These two keys make up the account's keypair.

#### Stellar's Features:

Our service utilizes Stellar's seamless transaction system to create smart contracts. Stellar has unique features that make it an ideal platform to develop our application on.  
- *Efficiency*  
Stellar’s network is efficient, having both fast transaction times and low fees. This is essential for a derivative market and is one of the main areas where Stellar shines versus other networks like Etherium.  
- *Decentralization*  
Unlike other blockchains, Stellar's network is truly decentralized. There is no governing body we need to rely on, as long as Stellar has users, our product will function.
- *[Anchors](https://www.stellar.org/developers/guides/concepts/assets.html)*  
Stellar has an anchor functionality that enables users to create custom assets on its ledger and tie them to real-world assets. We use this to create custom assets that allow users to trade their derivatives and write derivatives involving any asset.  
- *Flexible Transaction System*  
Stellar has a flexible transaction system that allows us to create the derivatives and make them trust-free, tradeable, and safe.  

[Stellar's website](https://www.stellar.org/developers/guides/walkthroughs/stellar-smart-contracts.html)

### Use Cases:

We would like to outline a few cases to help explain the use and value of the OptionBlox service.

1. **Currency Stabilization Use Case:**  
A primary concern for cryptocurrency holders is volatility. OptionBlox enables users to utilize financial derivatives to hedge against cryptocurrency volatility.

   Latera is a personal investor. He has read about the high-interest rates bitcoin (BTC) savings accounts offer, and would like to open one. However, the volatility of cryptocurrency is a major deterrent. He comes across a tool called OptionBlox that allows him to enter into a future contract guaranteeing him an exchange rate of 1BTC:$8000USD in 1 year time. He enters into the contract and opens a savings account with his BTC.

2. **Developing Country Use Case:**  
Investors in developing countries often do not have efficient global market access. They lack access to local brokers, international brokers often do not allow them to open accounts, it can be hard for them to obtain foreign currency, and governments can have regulations to prevent investing in foreign assets. OptionBlox allows parties to create derivatives on Stellar’s ledger and sell them to investors in developing countries, circumventing these obstacles.

   Adam is a citizen and resident of Vietnam. He would like to invest in AAPL calls but there are no local option brokers and foreign brokers do not accept the Vietnamese Dong (VND). Foreign currency exchange is illegal in Vietnam, making exchanging his VND for USD or other currencies difficult and costly. Adam finds out about OptionBlox and realizes it is the answer to his problems. Utilizing a cryptocurrency exchange, Adam exchanges his VND for BTC. Then he exchanges BTC for a BTC anchor on Stellar. He can now utilize his BTC token to purchase AAPL calls written by a hedge fund in the USA, achieving his investment goals.

3. **Carbon Credits Use Case:**\
Carbon emissions are a crucial issue today. One proposed way to handle them is by issuing carbon credits to companies. These credits govern how much carbon companies can emit and can be traded between companies in a market system, so they are used most efficiently. Using OptionBlox, with the help of a carbon credit anchor, companies could trade derivatives on their carbon credits.

   Xiao is an executive at a major battery producer. Business is booming, and she wants to expand operations, however, her company needs to purchase more carbon credits to do so. As a result, carbon credit price fluctuations in the future are a risk for this expansion. Xiao does some research and discovers Optionblox. She realizes she can use our product to purchase carbon credit futures, hedging her company against the risk of carbon credit price volatility. Her company enters into futures agreements to mitigate the risk and goes ahead with the expansion.

### OptionBlox's Solutions:
#### Derivatives:
OptionBlox features a range of tradeable decentralized derivative products
##### Covered Options
Our covered options are created using a network of accounts and preauthorized transactions. This protocol is based completely on Stellar's network and can operate without any input besides users submitting transactions. These options are European style.  

Below is a basic model showing the writing, sale, and exercise processes of a covered call with an underlying of 1 Bitcoin(BTC), and a strike price of 50 Lumens(XLM).

![alt text](https://github.com/mootz12/OptionBlox/blob/master/photos/writing%20sale%20exercise-covered(whitepaper).png "Writing/Sale/Excercise Covered Call")

##### Uncovered Options
Our uncovered options use a similar process as our covered options. The key difference is the holding account also serves as a margin account for the seller. We use an open-source code repository to operate the logic surrounding margin requirements. Stellar's native operations are not complicated enough to allow us to perform the logic on-ledger. Using a repository also increases efficiency.  We create an encrypted keypair for the repository to accomplish this securely. We do not have access to this keypair. We then add the repository's secret key as a signer on the holding account. This allows the repository to sign pre-defined operations for the holding account.

Below is a model showing the writing, sale, and execution process of an uncovered call. The call's underlying is 100 BTC,  it's strike price is 500 XLM, the initial margin requirement is 20%, and the minimum margin requirement is 15%. These options are European style.

![alt text](https://github.com/mootz12/OptionBlox/blob/master/photos/uncovered%20options-(whitepaper).png "Uncovered Options")

##### Futures
Our futures protocol expands on the uncovered options protocol. We use two margin and holding accounts, one for the buyer and one for the seller. We use the same open-source repository that we use with uncovered options to handle the margin and settlement operations. We settle our futures daily

Below is a basic model showing the writing, sale, execution, and exit of a 100XLM:10BTC future with a 20% initial margin requirement and a 15% minimum margin requirement

![alt text](https://github.com/mootz12/OptionBlox/blob/master/photos/futures-educational(whitepaper).png "Futures")

##### Forwards
Our forwards protocol operates in the same way as our futures protocol, the only difference is forwards do not rebalance daily.


#### Margin Accounts:
We offer margin accounts for organizations that want to provide their decentralized exchange users with margin. We utilize a global holding account that stores user's deposits and sends them a custom margin asset in exchange. The margin funds are deposited in user accounts where the repository is the only signer. The repository will only sign trustline operations for approved assets and buy/sell transactions. This prevents users from moving margin assets or assets they purchase out of this account. We apply margin requirement operations to this account.

Below is a basic model showing a margin account with a 50% margin, an initial deposit of 100xlm, and rebalancing required when the account loses 20% of its initial value.

![alt text](https://github.com/mootz12/OptionBlox/blob/master/photos/margin%20account%20(whitepaper).png "Margin Account Architecture")

### Security:

To ensure that our derivatives and margin accounts are secure we use a variety of Stellar's features.

- *Locking Accounts and Preauthorizing Transactions*  
In most of our protocols, we have some accounts preauthorize transactions then lock the accounts. This ensures that the only transactions they can post in the future are the preauthorized ones. We use this to lock funds in holding accounts until contract exercise.  
[More info](https://www.stellar.org/developers/guides/concepts/multi-sig.html)

- *Timebound Transactions*  
In all of our protocols, we use timebound transactions in the exercise process to ensure certain transactions cannot be submitted early. Submitting some transactions early would disrupt the exercise process.  
[More info](https://www.stellar.org/developers/guides/concepts/multi-sig.html)

- *Stellar Consensus Protocol*  
Stellar's consensus protocol rejects transactions when they do not align with the correct ledger state. For example, a user could not fill a sell offer if their account lacked the necessary funds.  
[More Info](https://www.stellar.org/developers/guides/concepts/scp.html)  

### Next Steps:

At Adventum we are in the beginning stages of building the OptionBlox backend and platform. While we are doing this we will be searching for potential investors and partnerships.