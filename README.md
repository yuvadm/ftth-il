# Israeli FTTH Plan Technical Details

Fiber-to-the-Home (FTTH) in Israel is provided to private consumers by several different telecom companies:

  - [Bezeq](https://www.bezeq.co.il/)
  - [Partner](https://www.partner.co.il/)
  - [Cellcom](https://cellcom.co.il/)
  - [Unlimited](https://www.unlimited.net.il/)

Each uses slightly different infrastructure and configurations. This repository documents the technical details for each telecom. Additionally, the goal for this repo is to provide details on the performance of each provider so that private customers can make smart decisions that consider which provider offers the best service.

## Partner

Partner markets their service as "private fiber" which means they use P2P instead of GPON. Effectively, most users do not notice significant performance speedup.

The fiber connection used is a simplex WDM LC-terminated fiber that uses 1490nm wavelength for TX and 1310nm for RX.

A reference SFP module that Partner provides is the [OPKAS1004](datasheets/OPKAS1004%20-%20DS_SFP-31W2Bah-DR(OPKAS1004)_SP.pdf).

### Devices

| Image | Model | Description | Datasheet | Status |
| ----- | ----- | ----------- | --------- | ------ |
| ![](imgs/OPKAS1004.01.png) | OPKAS1004 | SFP | [OPKAS1004%20-%20DS_SFP-31W2Bah-DR(OPKAS1004)_SP.pdf](datasheets/OPKAS1004%20-%20DS_SFP-31W2Bah-DR(OPKAS1004)_SP.pdf) | ✅ Vendor supplied |
