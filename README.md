<p align="center"><a href="https://github.com/overhide"><img src="./.github/logo.png" width="200px"/></a></p>

# ABOUT

The numerous [*overhide* GitHub repositories](https://github.com/overhide) constitute the OSS code of the [*overhide* system](https://overhide.io).

The [*overhide* system](https://overhide.io) is comprised of two main component categories:

1. *ledger-based authorization*
1. *data-store brokerage*

The *data-store brokerage* is the main deliverable of *overhide* and drives development of *ledger-based authorization*.

_**Introductory material is at https://overhide.io**_

_**Learn about the system in the [overhide repo](https://github.com/overhide/overhide).**_

# Repositories

## Ledger-Based Authorization Components

* [why?](https://overhide.io/2019/03/20/why.html)
    * motivation for *ledger-based authorization*
    * read this first
* [ledgers.js](https://github.com/overhide/ledgers.js)
    * browser library for integration of *ledger-based authorization* into apps & services
* [ledgers.js-demo](https://overhide.github.io/ledgers.js-demo/demo/login.html) ([repo](https://github.com/overhide/ledgers.js-demo))
    * a *demo* of a *ledgers.js* integration
* [ledgers.js-demo-serverless-dapp](https://overhide.github.io/ledgers.js-demo-serverless-dapp/dist/index.html) ([repo](https://github.com/overhide/ledgers.js-demo-serverless-dapp))
   * a *demo* of a *ledgers.js* integration with the [remuneration APIs](https://github.com/overhide/overhide/blob/master/docs/remuneration-api.md) running in a serverless back-end (Azure)
* [Remuneration APIs](https://github.com/overhide/overhide/blob/master/docs/remuneration-api.md)
* [overhide-ethereum](https://github.com/overhide/overhide-ethereum)
    * Ethereum implementation of *ledger-based authorization* [APIs](https://rinkeby.ethereum.overhide.io/swagger.html)
* US dollars ledger ([main network](https://ledger.overhide.io)) ([test network](https://test.ledger.overhide.io))
    * US dollars implementation of *ledger-based authorization* [APIs](https://test.ohledger.com/swagger.html)
    * closed source ledger enabling *ledger-based authorization* with fiat currencies: US dollars
    * see the [ledgers.js](https://github.com/overhide/ledgers.js) *demo* for example use/integration
    * uses [Stripe.com](https://stripe.com) for payment processing
    
> Note everything in *overhide* is OSS with the exception of *overhide-ledger*--the US dollars ledger.
>
> *Overhide-ledger* is closed source and has a pending patent application (No. 62817820) "PSEUDONYMOUS FIAT CURRENCY TRANSACTION LOGGER SYSTEM AND METHOD FOR PAYMENT GATEWAYS".  It covers the fiat-currency specific IP as summarized in the [*why* write-up](https://overhide.io/2019/03/20/why.html#what-does-overhide-ledger-do).

## Data-Store Brokerage Components

> All of the below broker components are still in early stages of development; all towards the fist release as a [*minimally viable product*](https://github.com/overhide/overhide/blob/master/docs/mvp.md).    

* [overhide](https://github.com/overhide/overhide) (specification)
    * overall documentation
    * [broker API documentation](TBD)
    * definitions
    * concepts
    * specifications

* [armadietto](https://github.com/overhide/armadietto) (remotestorage.io)
    * fork of remotestorage.io's storage server--armadietto
    * adding ledger-based authorization to this offering

# Community

Our sincere hope is to grow [*overhide*](https://overhide.io) together.

Please join us:

## [reddit :: r/overhide](https://www.reddit.com/r/overhide/)

## [twitter :: @overhideio](https://twitter.com/overhideio)
