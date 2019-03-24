<p align="center"><a href="https://github.com/overhide"><img src="./.github/logo.png" width="200px"/></a></p>

# ABOUT

The numerous [*overhide* GitHub repositories](https://github.com/overhide) constitute the OSS code of the *overhide* system.

The *overhide* system is comprised of two main components:

1. *data-store broker*
1. *ledger-based authorization*

The *data-store broker* is the main deliverable of *overhide* and drives development of *ledger-based authorization*.

Learn about the system in the [overhide repo](https://github.com/overhide/overhide).

# Repositories

## Data-Store Broker Components

* [overhide](https://github.com/overhide/overhide) (specification)
    * overall documentation
    * [broker API documentation](TBD)
    * definitions
    * concepts
    * specifications

> The broker components are still being developed towards the fist release as a [*minimally viable product*](https://github.com/overhide/overhide/blob/master/docs/mvp.md).    

## Ledger-Based Authorization Components

* [why?](https://github.com/overhide/ledgers.js/blob/master/why/why.md)
    * motivation for *ledger-based authorization*
    * read this first
* [ledgers.js](https://github.com/overhide/ledgers.js)
    * browser library for integration of *ledger-based authorization* into apps & services
    * a *demo* of such an integration
* [Remuneration APIs](https://github.com/overhide/overhide/blob/master/docs/remuneration-api.md)
* [overhide-ethereum](https://github.com/overhide/overhide-ethereum)
    * Ethereum implementation of *ledger-based authorization* [APIs](https://rinkeby.ethereum.overhide.io/swagger.html)
* US dollars ledger ([main network](https://ohledger.com)) ([test network](https://test.ohledger.com))
    * US dollars implementation of *ledger-based authorization* [APIs](https://test.ohledger.com/swagger.html)
    * closed source ledger enabling *ledger-based authorization* with fiat currencies: US dollars
    * see the [ledgers.js](https://github.com/overhide/ledgers.js) *demo* for example use/integration
    * uses [Stripe.com](https://stripe.com) for payment processing
    
> Note everything in *overhide* is OSS with the exception of *overhide-ledger*--the US dollars ledger.
>
> *Overhide-ledger* is closed source and has a pending patent application (No. 62817820) "PSEUDONYMOUS FIAT CURRENCY TRANSACTION LOGGER SYSTEM AND METHOD FOR PAYMENT GATEWAYS".  It covers the fiat-currency specific IP as summarized in the [*why* write-up](https://github.com/overhide/ledgers.js/blob/master/why/why.md#what-does-overhide-ledger-do).

# Community

Our sincere hope is to grow *overhide* together.

Please join us:

## [reddit :: r/overhide](https://www.reddit.com/r/overhide/)

## [twitter :: @overhideio](https://twitter.com/overhideio)