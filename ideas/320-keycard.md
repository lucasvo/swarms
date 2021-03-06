---
id: 320-keycard
title: Status Keycard
status: implementation
lead-contributor: guylouis
contributors:
  - Michele @bitgamma
  - Andrea @gravityblast
  - Dmitry @dmitryn
  - xFntesting @nastya
  - xFndesign @denis-sharpyn
budget:
- actual: xxx
- estimate: yyy
- currency: ETH/USD/SNT
---

# Swarm proposal

## Summary and Goal(s)

We want to give Status users control over their private keys, and offer them the possibilty to store them in a air-gapped secure device. This kind of control is provided by hardware wallets, however there is no hardware wallet on the market today that integrates with mobile apps, and hardware wallets are quite expensive. 

Javacard smartcards are a good platform to solve this issue: their inexpensive, provides  very high level of physical security (CC EAL5+), and are contactless (NFC) and thus work with Android apps. 

Our goal is to:
- manufacture such a smartcard, called Keycard,
- standardize a protocol 'Keycard API' for integration of clients with smartcards securing access to crypto assets
- propose an open source javacard applet 'Keycard applet'
- integrate Keycard with Status app

This swarm is about:
- Keycard applet
- Status software integration

## Communication


[#status-keycard](https://get.status.im/chat/public/status-keycard)


Weekly Sync, tuesday 11:00 AM Paris time

Weekly meeting notes https://notes.status.im/BSmOfT4qSuWLLXS6AuxcXQ

## Research

**Keycard applet**

closed

**Status software integration**

closed

## Specification

**Keycard applet**

closed

**Status software integration**

The specification for the Status integration is done

The use cases for the Status integration are:
1. sign transaction by tapping card + entering PIN
2. login into account by tapping card and entering PIN
3.  export of the whisper key from the card to the app (goal : not store the whisper private key in Flash at anay time on the app)
4. export of the password used to encode the database from the card to the app 

Specification consists of: 

User flow wireframes

https://docs.google.com/document/d/1w9GGtsAC8H3B563iRi52evOYMGNOfBlVh3Ay4aFuluc/edit

Screens UX Flows in Figma

https://bit.ly/2NdxoUB


## Implementation

**Keycard applet**

closed

**Status software integration**

Alpha stage: up to 28/02/2019
Beta stage: 01/03/2019 (Beta success consists of functional availability of use cases 1-2-3-4)

## Maintenance



## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
