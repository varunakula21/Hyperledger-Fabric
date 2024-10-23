# Hyperledger Fabric Asset Management System

[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/hyperledger/fabric/badge)](https://scorecard.dev/viewer/?uri=github.com/hyperledger/fabric)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/955/badge)](https://bestpractices.coreinfrastructure.org/projects/955)
[![Go Report Card](https://goreportcard.com/badge/github.com/hyperledger/fabric)](https://goreportcard.com/report/github.com/hyperledger/fabric)
[![GoDoc](https://godoc.org/github.com/hyperledger/fabric?status.svg)](https://godoc.org/github.com/hyperledger/fabric)
[![Documentation Status](https://readthedocs.org/projects/hyperledger-fabric/badge/?version=latest)](http://hyperledger-fabric.readthedocs.io/en/latest)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/hyperledger/fabric/verify-build.yml?branch=main&label=build%20-%20main)](https://github.com/hyperledger/fabric/actions/workflows/verify-build.yml)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/hyperledger/fabric/verify-build.yml?branch=release-2.5&label=build%20-%20release-2.5)](https://github.com/hyperledger/fabric/actions/workflows/verify-build.yml)
[![Security vulnerability scan](https://github.com/hyperledger/fabric/actions/workflows/vulnerability-scan.yml/badge.svg?branch=main)](https://github.com/hyperledger/fabric/actions/workflows/vulnerability-scan.yml)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/hyperledger/fabric)](https://github.com/hyperledger/fabric/blob/main/go.mod)
[![GitHub Release](https://img.shields.io/github/v/release/hyperledger/fabric)](https://github.com/hyperledger/fabric/releases)

## Overview

**Hyperledger Fabric** is a **Graduated** project under the Hyperledger umbrella, designed for distributed ledger solutions. Its modular architecture provides high levels of confidentiality, resiliency, flexibility, and scalability. Hyperledger Fabric allows for pluggable implementations of various components, accommodating the complexities of different economic ecosystems.

This platform offers a uniquely elastic and extensible architecture, setting it apart from other blockchain solutions. Building on a fully-vetted, open-source framework, Hyperledger Fabric is an ideal starting point for enterprise blockchain initiatives.

This repository contains the implementation of a blockchain-based asset management system using Hyperledger Fabric. This project was developed as part of an internship assignment, focused on creating, updating, and tracking assets for a financial institution while ensuring security, transparency, and immutability.

## Key Features:
Asset Management: Supports creation, updating, and querying of assets representing accounts with attributes such as DEALERID, MSISDN, MPIN, BALANCE, STATUS, TRANSAMOUNT, TRANSTYPE, and REMARKS.
Transaction History: Retrieves complete transaction history for assets, allowing the institution to track and manage asset-related transactions.
Blockchain Network Setup: Hyperledger Fabric test network was set up and used for developing and deploying the system.
Smart Contract Development: A smart contract was created and deployed to manage the assets and their transactions.
REST API Integration: A REST API was developed to invoke the smart contract, enabling easy interaction with the blockchain network.
Docker Image: The REST API was containerized using Docker for simplified deployment and scalability.

## Technology Stack:
Blockchain Framework: Hyperledger Fabric
Smart Contract Language: Golang
REST API: Express (Node.js)
Containerization: Docker

## Setup Instructions:
1.Setup Hyperledger Fabric test network.
2.Deploy the smart contract.
3.Use the REST API to invoke the smart contract.
4.Monitor the blockchain network for transaction history and asset updates.


## Releases

Hyperledger Fabric provides periodic releases with new features and improvements. Certain releases are designated as **Long-Term Support (LTS)**, ensuring that important fixes are backported during overlap periods.

### Current LTS Release:
- **[v2.5.x](https://hyperledger-fabric.readthedocs.io/en/release-2.5/whatsnew.html)**

### Historic LTS Releases:
- **[v2.2.x](https://hyperledger-fabric.readthedocs.io/en/release-2.2/whatsnew.html)** (maintenance ended February 2024)
- **[v1.4.x](https://hyperledger-fabric.readthedocs.io/en/release-1.4/whatsnew.html)** (maintenance ended April 2021)

For complete release notes, visit the **[GitHub releases page](https://github.com/hyperledger/fabric/releases)**.

## Documentation and Getting Started

To familiarize yourself with Hyperledger Fabric, visit our comprehensive online documentation:
- **[Getting Started with v2.5](http://hyperledger-fabric.readthedocs.io/en/release-2.5/)**
- **[Previous Versions](http://hyperledger-fabric.readthedocs.io/en/release-2.4/)**

We recommend that first-time users start with the **Getting Started** section to understand the components and basic transaction flow.

## Contributing

We welcome contributions to Hyperledger Fabric in various forms. There’s always plenty to do! Check our [contribution guidelines](http://hyperledger-fabric.readthedocs.io/en/latest/CONTRIBUTING.html) for more details on how to get involved.

## Community

Engage with the Hyperledger community:
- **[Hyperledger Community Meetup](https://www.meetup.com/pro/hyperledger/)**
- **[Mailing Lists and Archives](http://lists.hyperledger.org/)**
- **[Discord Chat](https://discord.com/invite/hyperledger)**
- **[Issue Tracking](https://github.com/hyperledger/fabric/issues)**

## License

Hyperledger Fabric source code is available under the **Apache License, Version 2.0 (Apache-2.0)**, and documentation files are under the **Creative Commons Attribution 4.0 International License (CC-BY-4.0)**.
