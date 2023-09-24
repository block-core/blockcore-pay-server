# Blockcore Pay Server

A very basic service that allows anyone to sell digital products, can be used behind Blockcore Market.

## Concept

The idea behind this software service is to allow anyone to run an instance, setup a wallet to be used and then 
issue various digital products that can be sold. Users must identity using their DIDs and perform payment 
using a cryptocurrency.

When payments are observed on the blockchain, the service wallet will automatically issue an VC (Verifiable Credential) 
that attests the product belongs to the DID of the user.

Reselling digital products require that the user goes back into the website and then issues and VC to the new owner, which 
will be persisted by the Pay Server and a new VC will be issued claiming ownership to the new DID.

# Technology

The Pay Server is built on Node.js and uses SQLite for storage.
