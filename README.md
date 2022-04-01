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

| Image | Model | Description | Status |
| ----- | ----- | ----------- | ------ |
| <img src="imgs/OPKAS1004.01.png" width="100"> | [OPKAS1004]((datasheets/OPKAS1004%20-%20DS_SFP-31W2Bah-DR(OPKAS1004)_SP.pdf)) | SFP-31W2Bah(SM-10)-TX1490 RX1310-Purpule | :heavy_check_mark: Reference |
| <img src="imgs/75336.main.jpg" width="100"> | [FS.com #75336](https://www.fs.com/products/75336.html) | Generic Compatible 1000BASE-BX BiDi SFP 1490nm-TX/1310nm-RX 10km DOM LC SMF Transceiver Module | :grey_question: Pending |
