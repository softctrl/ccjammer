![TigeRFID](_assets/tigerfid.jpg)
# CC Jammer

## Introduction

This repository has been created in honor of my father, Touraj Ghaffari. He founded [ActiveWave, Inc.](http://www.activewaveinc.com/) in 2001. It was his life work and something he loved and enjoyed thoroughly. He also loved spreading knowledge. In honor of that principle, we, his three sons, have open-sourced everything associated with his CC Jammer under the [Apache 2.0 license](license). We hope this release helps you acheive your dreams.

**Note: This system intentionally interferes with RF signals. Please check your local laws to determine if this is a device you can legally possess/create. From our understanding, there is nothing that made this illegal to possess/create in the US, but we provide no guarantees. Use at your own risk.**

## What is this?

The CC Jammer's purpose is to protect credit cards and other sensitive items that are NFC-enabled. My father made two videos, showing how they work:

* [In Wallet](https://www.youtube.com/watch?v=5VIWjBv9iFk)

* [Out of Wallet](https://www.youtube.com/watch?v=TXtZF7adKfY)

_Note: The product was being called the RFID Guardian. The project was called "ccjammer" prior to getting a name, so we're taking it back to its roots._

## What is the project's current state?

We believe it is ready to go, as-is. However, we hope the public can review and confirm that fact - and then continue to improve on it.

## How can I get involved?

### Setup

1. Determine how many ccjammers you would like to manufacture.

2. Use the [BOM files](bom-files) to figure out how many parts you need

3. Manufacture the parts using the [Protel files](protel-files). All the PCBs were designed using [Protel (now known as Altium)](http://www.altium.com/).

4. Share whatever improvements you make!

### Skillsets required

#### Software

* Designing PCBs

#### Hardware

* Antenna design

* Soldering

### Assistance required

* We are looking for help to remove some of the old files. We included a few previous versions of each device in order to provide people with some history. We would like to remove all those older files and create a single-source-of-truth folder for each device.

* We are looking for help to improve documentation. In particular, we would like help to create a guide to stand-up a demo system based on the minimum requirements, a guide to manufacutre each device, and a guide to troubleshoot each device.

* We would like people's thoughts on whether the current structure is best or if it would be preferrable to have each device seperated out like the sealTag.

* We would like people's thoughts on the best way to display the BOMs. Should we convert them to markdown? Use a Google Sheet? Something else?

## Contents

1. [BOM files](bom-files)

2. [Protel files](protel-files)

    a. [Rev0](protel-files/rev0)

    b. [Rev1](protel-files/rev1)

    c. [Rev2](protel-files/rev2)

## Fun Touraj Fact

When asked how old he was, Touraj loved to say he was 25. We launched this on the 25th of January so it is always associated with his eternal age.
