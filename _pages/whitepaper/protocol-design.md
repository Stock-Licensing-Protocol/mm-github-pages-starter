---
permalink: /whitepaper/protocol-design/
title: "Protocol Design"
author_profile: false
sidebar:
    nav: "docs"
classes: wide
toc: false
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/whitepaper-header.jpg
  overlay_filter: .7
  caption: "Photo: [Tierney](https://stock.adobe.com/ca/contributor/202206661/tierney)"
  actions:
    - label: "<i class='fas fa-download'></i> Download Full Whitepaper PDF"
      url: "/assets/documents/Stock-Licensing-Protocol-Whitepaper.pdf"
excerpt: >
  <br />
---

# Protocol Design

The Stock Licensing Protocol will consist of multiple components that are
outlined below. All of these components will be open source and developed and
maintained by the stock licensing protocol community.

The NFT and tokens will be deployed on an environmentally friendly proof of
stake EVM compatible blockchain. Stock marketplaces and creator technology
partners will be able to choose centralized or decentralized technologies to
meet the needs of creators and License Buyers.

This document provides a high-level description of each Stock Licensing Protocol
component, but technical specifications are out of scope of this document.
Technical specifications and open-source code will be provided during the
implementation of each component.

## NFTs and Tokens

The Stock Licensing Protocol requires multiple NFTs and one token to meet the
needs of all participants in the Stock Licensing Protocol community. The utility
of each token is outlined below.

### Stock Licensing Protocol Token

The stock licensing protocol token will provide incentives and governance of the
protocol. Each stock licensing NFT will require a predetermined number of tokens
to mint. Requiring tokens to mint stock licensing NFTs will reduce spam and
copyright infringement within the protocol.

In addition, once the Stock Licensing Protocol DAO has been established, token
holders will be able to influence protocol governance decisions by voting on
protocol changes including:

-   Allocation of the DAO treasury
-   Changes in pricing for License Credits
-   Amount of Stock Licensing Protocol Token required to mint a Stock Licensing
    NFT
-   Changes to the protocol service fee

### Stock Licensing NFT

The Stock Licensing NFT represents the licensable stock asset. Creators will
mint a stock licensing NFT for each of their licensable assets. Minting a stock
licensing NFT will require a predetermined amount of Stock Licensing Protocol
Tokens to prevent spam and copyright infringement. These tokens will be held by
the smart contract while the NFT is available on sale. If the owner decides to
burn a stock licensing NFT then the deposited Stock Licensing Protocol Tokens
will be returned to the owner of the NFT.

The Stock Licensing NFT will be used to sell licenses to License Buyers by
receiving payment from buyers and automatically distributing the payment to the
relevant wallets. The owner of the Stock Licensing NFT will receive the revenue
from the sale so most creators will never sell or transfer the Stock Licensing
NFT after creating. If they do sell or transfer their Stock Licensing NFT then
the new owner will receive revenue from any future license sales.

### Non-Fungible License

A Non-Fungible License represents a license granted to a License Buyer to use an
asset within the conditions specified in the Stock NFT License Agreement. A
Non-Fungible License can only be minted by Stock Licensing NFTs when a License
Buyer sends the Creators the specific purchase price. The blockchain smart
contract ensures the license NFT is minted only after the creator receives the
purchase price. The Stock Licensing Protocol will also add a protocol service
fee which is initially planned at 2.5% and will be deposited into the Stock
Licensing Protocol Dao treasury which will be controlled by the stock licensing
protocol community via the DAO governance process.

Non-Fungible License are not transferable and allow the owner of the NFT to
download and use the asset per the license agreement.

### License Credit

It is common practice for centralized stock agencies to provide licenses at
substantially reduced prices if License Buyers commit to a monthly subscription
or to purchase multiple licenses. The Stock Licensing Protocol will support
volume discounts via the License Credits. License Credits will be implemented as
an NFT because each credit will have a unique price paid for it.

License Buyers can purchase License Credits at a volume discount, the price of
license credits will be initially set at a competitive price compared to
centralized stock companies but can be changed by the Stock Licensing Protocol
community via the governance process. License Credit NFTs are minted when
purchased and the purchase tokens will be stored in the NFT contract. A License
Credit NFT can be used to purchase a license from a creator who has opted to
accept License Credit NFTs as payment. When a License Buyer spends a License
Credit NFT the price paid for the credit is transferred from the smart contract
to the creator and the License Credit NFT is burnt.

## Stock Licensing Metadata Standard

Every NFT requires a token URI that references a JSON file containing
information about the NFT. There is a standardized JSON format for NFTs
supported by current NFT marketplaces. The Stock Licencing Protocol will include
a more specific metadata standard that will conform to the format currently used
by NFT marketplaces but will also include additional data to support rich search
features expected by stock License Buyers.

## Creators Licensing NFT Studio

Building a JSON file that conforms to the Stock Licensing Metadata Standard and
interacting with smart contracts on blockchains is a very technical task and
typically would be done with a separate tool. The Stock Licensing Protocol will
include an open source user interface to allow creators to easily mint and
manage their Stock Licensing NFTs. Open sourcing the Creators Licensing NFT
Studio will allow the community to suggest and develop feature requests. The
code for the studio can also be used as a reference for centralized tools
looking to add NFT licensing features to their products.

## Stock NFT License Agreement

The Stock Licensing Protocol will include a license agreement stating exactly
which rights are given when an asset is licensed. The initial licensing
agreement will be a royalty free license with similar terms to popular
centralized stock agencies. The accepting the license agreement will be required
to create a Stock Licensing NFT or purchase a Non-Fungible License.

## Search Infrastructure

It is important for License Buyers to be able to quickly find images needed for
their project. With centralized technologies, supporting search requires
building and maintaining an indexing server which requires a significant amount
of engineering effort and cost. The Stock Licensing Protocol will support
popular decentralized indexing services by publishing an open-source code and
documentation on how to easily integrate with these services.

## Reference NFT Stock Marketplace

The goal of the protocol is for many stock marketplaces to be developed and
deployed by entrepreneurs and marketers that all reference the Stock Licensing
Protocol collection. To reduce the development costs of building an NFT stock
marketplace, a Reference NFT Stock Marketplace will be developed and deployed.
The marketplace will be open sourced, and deployment of the marketplace will be
encouraged by providing technical support and possible economic incentives.

## Secure File Storage Protocol

The Secure File Storage Protocol will store full size stock assets and only
allow access to those files to users who own a purchased Non-Fungible License.
This will allow creators to control the access to the full-size files which can
deter copyright infringement. However, use of the secure file storage protocol
will be optional because the Stock NFT License Agreement will protect creators
from copyright infringement by specifying the usage allowed by the License
Buyers. Creators who do not utilize the Secure File Storage Protocol can provide
links to the stock assets in the Stock Licensing Metadata.

## Digital Asset Antispam and Copyright Protection Protocol

The Stock Licensing Protocol will be deployed on a low gas fee blockchain to
allow asset creators to mint Stock Licensing NFTs for an insignificantly small
gas fee. This will benefit creators but will also open the protocol to spam NFTs
and copyright infringement. We have seen this on other platforms like the
Opensea where it is estimated 80% go gas free NFT mints were plagiarized, spam
or fake [[3]](https://www.theblockcrypto.com/linked/132511/opensea-reveals-that-over-80-of-its-free-nft-mints-were-plagiarized-spam-or-fake). So, the Stock Licensing Protocol needs anti-spam and copyright protection built into the protocol at the smart contract level.

The Stock Licensing Protocol Token will be the primary method for limiting spam
and copyright infringement by making these activities prohibitively costly to
bad actors. Minting a Stock Licensing NFT will require a predetermined amount of
Stock Licensing Protocol Tokens. Initially the Stock Licensing Protocol Tokens
will be fairly distributed to creators with libraries of existing stock assets.
The intent will be for these creators to use the tokens to create their Stock
Licensing NFTs because there will not be a market to sell the tokens. These
creators will be incentivized to use the tokens to sell their own creative works
and not spam the protocol or infringe on others' copyright.

As the success of the protocol grows, Stock Licensing Protocol Tokens will be
available for purchase on decentralized marketplaces. As a result, a bad actor
wanted to spam the system will be required to purchase tokens to spams.

It will be possible for copyright holders to submit DMCA takedown notices or for
community members to flag NFTs as spam. If a DMCA takedown notice is successful,
then the tokens used to create the Stock Licensing NFT will be forfeited and not
returned to the creator (who is a bad actor). This will enforce an economic
disincentive to bad actors. It will also be possible for marketplaces to flag
Stock Licensing NFTs as fraudulent and the Search Infrastructure will provide
streamlined ways to remove flagged NFTs from search results.

Initially Creator Technology Partners will be responsible for flagging Stock
Licensing NFTs as spam or copyright infringement but the intent is for future
versions of the protocol to create a decentralized enforcement mechanism where
anyone in the Stock Licensing Protocol community can contribute to ensuring bad
actors are not profiting from the protocol.

## Stock Licensing Protocol DAO

A DAO will be created to govern the Stock Licensing Protocol with an initial
goal of encouraging growth and innovation on the protocol. The Stock Licensing
Protocol DAO will be able to make changes to the protocol. These types of
changes include:

-   Allocation of the DAO treasury
-   Changes in pricing for License Credits
-   Amount of Stock Licensing Protocol Token required to mint a Stock Licensing
    NFT
-   Changes to the protocol service fee
-   Enforcing DMCA takedowns and preventing spam

The DAO will be governed with a voting process where Stock Licensing Protocol
Token holders will be able to vote on improvement proposals in a decentralized
manner. A small percentage of every license fee will be distributed to the
treasury for operations and maintenance. More details on the specifics of the
DAO and voting structure will be provided in future documentation.