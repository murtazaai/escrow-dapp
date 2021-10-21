# Summary
This is a small Escrow DApp (Decentralized app) using Solidity and Web3.js.

## The app has these functionalities
 
  - A Buyer and a Seller confirm and agree on the terms of a sale of a Seller's product. The Buyer places Ethereum currency into the smart contract - this provides buyer's proof-offunds to the seller.
  - The Seller sees that the buyer has enough funds and ships the product to the Buyer producing an evidence of shipment to an independent third party called Escrow Agent.
  - Escrow Agent sees the evidence of shipment and initiates the transfer of the funds stored in the escrow to the Seller. The transaction is now complete.
  - In case the seller does not produce an evidence of shipment to the Escrow Agent then Escrow Agent returns the funds from escrow to the Buyer. Buyer receives his/her money back.
  - Escrow Agent can get a small fee of the transaction amount for his/her impartial arbitration.
