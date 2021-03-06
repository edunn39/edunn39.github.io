---
layout: post
title: "Blockchain"
date: 2017-03-05
---

When your average Joe wants to send or receive money from his bank account, he either initiates a transfer or sits back and waits. When a bank wants to send or receive money, the process is much more complicated.

The main complication is that many customers hold accounts with a bank B, and the bank holds many accounts at other banks B'. When B finds that one of its accounts at B' has received a payment, B needs to attribute those funds to an account. In order for this to happen, B needs to record the funds it expects to receive, so that when it receives a message from B' indicating that the funds have been delivered, B can match those funds against the correct account. These "records" are generally refered to as "books"; the messages from B' are generally refered to as "banks."

The vast majority of payments are made via the SWIFT network. SWIFT is a standardized messaging system in which certain fields are expected to be populated in specific ways, depending on the type of message. Unless a bank deals directly with other international banks, that bank's payments and receipts will go through another bank that has the appropriate connections to transfer funds internationally. As you can imagine, it may take several hops to go from a regional bank in one country to a regional bank in another country.

To make the problem worse, the payment message received by bank B was generated from the party making the payment. In an ideal world, the message would contain all relevant information to complete the transfer of funds - particularly the account number of the final beneficiary (the intended recipient of the funds). However, the world is not ideal, and the banking industry spends millions, if not tens of millions of dollars every year investing in the reconciliations process. This investment is not optional; if a bank were to perform poorly at reconciling, client accounts would not be reflected correctly on a daily basis, and clients would not want to bank with that institution. As it is currently, the accuracy rate hovers around 99.9% - but this could still leave hundreds of payments reconciled incorrectly each day. While automation has certainly helped the process, there is significant risk of incorrect reconciliations, which need to be monitored closely.

There are a number of other problems which banks must address when sending and receiving funds:

1) Verify that they are not enabling money launderers

2) Verify that they are not enabling terrorists

3) Verify that the received payment was not an honest mistake from the sender

4) Verify that the sent payments are sent correctly

With all of these complications, you might think there should be a better way. And there is; it is called "blockchain." Blockchain simplifies many of the existing problems with payments and receipts, but it does come with a few complications.

Blockchain is the ledger system that supports bitcoin and many other forms of digital currencies and contracts. There is plenty of information about blockchain and bitcoin online, so if you are new to these concepts please skim a few articles to understand the basics. However, the blockchain need not be restricted to digital currencies; banks transact money digitally every day, even though the currencies they use are very real (of course, there are various checks to make sure that banks can find the liquidity to cover their positions at the end of the day).

By Google's definition, a ledger is "a book or other collection of financial accounts of a particular type." When banks reconcile payments and receipts, they are reconciling these messages against their own ledger. Every bank has their own ledger system, and they all essentially have the same functionality. But what if everyone relied on the same ledger? Then banks would not have to send and decipher messages all day, trying to match their own books with hundreds of thousands of bank messages. Furthermore, there would be no time delay between the bank receiving a client's funds, and the bank being able to apply the funds to that account. Nor would there be issues with funds attributed to the wrong account, as the transaction would clearly identify the final beneficiary account. Transaction costs would decrease significantly. And if the blockchain whitelists certain accounts as trustworthy, money launderers and terrorists could be excluded from transacting. Finally, many regulatory reporting requirements will be immediately satisfied simply by inspecting the blockchain's history.

There are many reasons that blockchain has not been implemented yet.

1) Driving consensus among competing organizations is incredibly difficult. Even if there is financial gain for both sides, it is not certain that blockchain will be adapted internationally (for some reasons below). Banks do not want to take this risk; they will adapt the technology when it becomes obvious that this is the future.

2) Who would own blockchain? Some entity or entities would have to develop and implement blockchain. How would the cost of a transaction be set? If there is not sufficient competition, blockchain companies could monopolize the industry once banks are completely reliant.

3) How secure is blockchain? Could a malicious entity hack bitcoin? What is the worst problem they could cause? Fortunately the extent of damage would be easily discernable, as every transaction is recorded. But what if the funds are withdrawn from the account before the fraudulent transactions are detected?

4) How would taxes work, especially internationally? There are many international, national, and state taxes that are applied to any payments. Currently, it is the responsibility of the sender to withhold applicable taxes, especially for individuals. How will tax rules be implemented in a system that allows for direct monetary transfers?

Why do we even need banks if we have bitcoin? The short answer is, we don't. Go buy some bitcoins (full disclosure: I currently have none). The long answer is that there are advantages to having different currencies for different countries, with banks as intermediaries. To begin with, physical currency is liquid, anonymous, and backed by the country. During economic trouble, a country's monetary policy could incentivize citizens to spend more, spend less, or print more money (causing inflation) to pay off international debts. The value of bitcoin is quite volatile and will be for some time; it would have value only because everyone agrees it has value. Banks can verify that their customers are neither terrorists nor money launderers, and only these whitelisted clients would be able to transact via blockchain freely. Finally, banks provide more services than just money transfers, such as loans, credit scores (dependent on bank account histories), and converting funds to physical cash.

There are a number of other uses for blockchain which I will mention but not discuss in depth. Blockchain can be used for many types of contracts beyond just monetary transactions. For example, if the blockchain supported equities as well as cash, blockchain could be used to structure options trades between two accounts automatically (this could create issues with margin and counterparty risk). Blockchain could also be used to sign contracts where an independent third party verifies the transaction of some physical good in exchange for money. These are just a few possibilities, but there are many more.
