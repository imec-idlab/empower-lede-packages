EmPOWER: Mobile Networks Operating System
=========================================

### What is EmPOWER?
EmPOWER is a new network operating system designed for heterogeneous mobile networks.

### Top-Level Features
* Supports both LTE and WiFi radio access networks
* Northbound abstractions for a global network view, network graph, and
  application intents.
* REST API and native (Python) API for accessing the Northbound abstractions
* Support for Click-based Lightweight Virtual Networks Functions
* Declarative VNF chaning on precise portion of the flowspace
* Flexible southbound interface supporting WiFi APs and LTE eNBs

Checkout out our [website](http://5g-empower.io/) and our [wiki](https://github.com/5g-empower/5g-empower.github.io/wiki)

This repository includes the EmPOWER packages for LEDE 17.01.

Code is released under the Apache License, Version 2.0.

### How to install

```
  $: cd $TOPDIR
  $: echo 'src-git empower https://github.com/5g-empower/empower-lede-packages.git' >> feeds.conf.default
  $: ./scripts/feeds update empower
  $: ./scripts/feeds install -a -p empower
```
