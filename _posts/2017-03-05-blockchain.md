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

What it is.

Simplifications.

Complications.

Why not yet adopted.

Other uses (not discussed in depth).
