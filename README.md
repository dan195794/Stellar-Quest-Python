# Stellar-Quest-Python
Stellar Quest Python Solutions :D

### Solutions for the following challenges:

# Quest 1

* Challenge 1: Create and fund a Stellar account

In this challenge your task is to create and fund a brand new Stellar account ************* (seen below) with 1000 XLM on the testnet.

* Challenge 2: Make a payment from your Stellar account

In this challenge, your task is to make a 10 XLM payment from the Stellar account ************* (seen below) you funded in challenge 1.

* Challenge 3: Store some arbitrary data in your Stellar account

Stellar allows you to store arbitrary data in the form of key : value pairs. In this challenge, you're tasked with adding a key of Hello and a value of World as a data attribute on your account. ************* (seen below).

* Challenge 4: Add multisig to your account and make use of it in a transaction

In this challenge, your task is to add and then make use of multisig on your account ************* (seen below).

* Challenge 5: Create a custom asset and send it to your account

In this challenge, your task is to create and send a custom asset to your account ************* (seen below).

* Challenge 6: Create an offer to sell your custom asset for XLM

In this challenge, your task is to create an offer to sell your custom asset for XLM.

* Challenge 7: Make use of a channel account to make a payment

In this challenge, your task is to submit a payment operation from your account ************* (seen below), but to use a separate source account to pay the fee and sequence number for the transaction.

* Challenge 8: Acquire custom asset via a path payment

In this challenge, your task is to acquire SRT from its issuing account ************* via a path payment operation.

-----

# Quest 2

* Challenge 1: Create and fund a Stellar account

In this challenge your task is to create and fund a brand new Stellar account ************* (seen below) with 5000 XLM on the testnet.

* Challenge 2: Construct and execute a multi-operational transaction

In this challenge your task is to create a multi-operational transaction which creates a custom asset trustline on your account and pays that asset to your account from the issuing account all in the same transaction.

* Challenge 3: Create and submit a fee bump transaction

In this challenge your task is to create and execute a fee bump transaction which consumes the sequence number from your account ************* (seen below) but the transaction fee from some other account.

* Challenge 4: Create a claimable balance

Today you've gotta sort out how to create a claimable balance that is only claimable by you and only claimable after the next challenge.

* Challenge 5: Claim your claimable balance

This challenge is to "simply" claim that balance and get your XLM back.

* Challenge 6: Sponsor the absolute minimum balance for a new account

In this challenge your task is to create a brand new 0 XLM balance account with the absolute minimum balance sponsored by your ************* account (seen below).

* Challenge 7: Revoke account sponsorship for the account you're sponsoring

In this challenge you need to revoke account sponsorship for the account you're currently sponsoring.

* Challenge 8: Create and host a stellar.toml file for your account

In today's challenge your task is to create, host and link to a stellar.toml file with an SQ02_EASTER_EGG field containing the text: <FOUND ON STELLAR QUEST>

-----

# Quest 3

* Challenge 1: Make use of a sequence number bump operation in a transaction

In today's inaugural challenge you must submit a transaction from your account, making use of the sequence number bump operation.

* Challenge 2: Submit a transaction containing 100 operations

Your challenge today is to successfully orchestrate and submit a transaction stuffed full of 100 operations.
  
* Challenge 3: Submit a hash signed transaction
  
In today's challenge your task is to add a very specific and special sha256 hash signer to your account and then to submit a second transaction using that signer to remove itself as a signer from the account. A sort of one time use key if you will.
  
* Challenge 4: Submit a pre-authorized transaction
  
Pre-authorized transactions are a fantastic way to get around the somewhat cumbersome issue of multisig coordination. Just add a transaction hash as a signer to your account and then pass along that XDR to any other signers for additional signing or final submission.

* Challenge 5: Successfully submit a clawback operation
  
It's the Ctrl+Z for blockchain payments. The mechanic for undoing mistaken or fraudulent payments. Once an issuer and trustline have been created under the asset clawback umbrella the issuer has the power to "clawback" any amount of that asset back into the issuing account effectively burning it from existence.

* Challenge 6: Mint a Stellar Quest style NFT

Today's challenge will be difficult so prepare yourself. Take breaks, deep breaths, walk away for awhile if you need to. Don't stress it, the rewards will be worth the effort.

* Challenge 7: Acquire and make use of a SEP-0010 JWT

Today's task will be to acquire a SEP-0010 JWT and then embed that JWT back into your account's () manageData fields in identical fashion to how we embedded the NFT data in the previous 
quest.

* Challenge 8: Use SEP-0006 to acquire some MULT from testanchor.stellar.org

Your task today will be to use SEP-0006 to request a deposit of MULT issued by GDLD...FSMM from the testanchor.stellar.org endpoint.

-----

### Learn Level 1

* Challenge 1: Create an account on the Stellar network

In this quest, your challenge is to create an account by using the createAccount operation with the Quest Keypair located in the box on the right-hand side of this screen. 


* Challenge 2: Payment

Send an amount of a specific asset to a destination account

In this quest, your challenge is to perform a payment operation where you’ll submit a transaction containing that payment operation on the Stellar test network from the Quest Account to another account.


* Challenge 3: Change Trust

Create a trustline between two accounts for a designated asset

In this quest, your challenge is to establish a trustline between the Quest Account and another account for a specific asset using the changeTrust operation.

* Challenge 4: Manage Offers
Create an offer to buy or sell a specific asset for another

In this quest, your challenge is to open a buy or sell offer on the Quest Account using the manageBuyOffer, manageSellOffer or createPassiveSellOffer operation.

* Challenge 5: Path Payments

Send or receive an asset that is different from the received or sent asset

In this quest, your challenge is to successfully send a path payment from the Quest Account to another account on the Stellar test network using the pathPaymentStrictSend or pathPaymentStrictReceive operation. Please note the sent asset must be different than the received asset.
