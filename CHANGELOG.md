# Changelog

## [15.23.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.22.0...v15.23.0) (2023-06-13)


### Features

* **add:** 3RSNL02043Z ([#5875](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5875)) ([f5c68ac](https://github.com/Koenkk/zigbee-herdsman-converters/commit/f5c68ac048bcccb247e3800c25e393031b2e6c01))
* Allow to set more sensitivity levels for TuYa TS0210. https://github.com/Koenkk/zigbee2mqtt/issues/17977 ([a6ae4fd](https://github.com/Koenkk/zigbee-herdsman-converters/commit/a6ae4fd73b6e0d54a0f9ba053a51307d1e0548c6))
* Support OTA for Moes MS-108ZR [@cserem](https://github.com/cserem) https://github.com/Koenkk/zigbee-OTA/pull/325 ([1e9c995](https://github.com/Koenkk/zigbee-herdsman-converters/commit/1e9c9958da8dad118cd9128c105535c30d2638ea))


### Bug Fixes

* Fix LifeControl MCLH-04 battery % incorrect. https://github.com/Koenkk/zigbee2mqtt/issues/18007 ([1d4e3cc](https://github.com/Koenkk/zigbee-herdsman-converters/commit/1d4e3cc732397fe1a2cd7ba7075f888d404ba3dd))

## [15.22.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.21.2...v15.22.0) (2023-06-12)


### Features

* **add:** 929003128401 @KHOne23 https://github.com/Koenkk/zigbee2mqtt/issues/17981 ([2966ed2](https://github.com/Koenkk/zigbee-herdsman-converters/commit/2966ed2473639de61a2d66a9eb3e8883eb5cbf38))
* **add:** 968.93 [@gritche2](https://github.com/gritche2) https://github.com/Koenkk/zigbee-herdsman-converters/issues/5876 ([004d872](https://github.com/Koenkk/zigbee-herdsman-converters/commit/004d87258114cb7a91716381b2370838e5128a84))
* **add:** NAS-AB06B2 ([#5878](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5878)) ([9ce2bea](https://github.com/Koenkk/zigbee-herdsman-converters/commit/9ce2beadec6389d641475e4c3350e61940638f5c))
* **add:** SIN-4-1-20_LEX ([#5868](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5868)) ([3541b57](https://github.com/Koenkk/zigbee-herdsman-converters/commit/3541b57f5cd3d5c8f02a5ff369bf6b8d8644ed06))
* **detect:** Detect `_TZ3000_rqbjepe8` as Nous A4Z ([#5879](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5879)) ([2f00e18](https://github.com/Koenkk/zigbee-herdsman-converters/commit/2f00e18dee8f66bf2407a6913a052af433715020))
* **detect:** Detect `_TZE200_leaqthqq` as TuYa TS0601_switch_5_gang. https://github.com/Koenkk/zigbee2mqtt/issues/17969 ([1e7eb70](https://github.com/Koenkk/zigbee-herdsman-converters/commit/1e7eb7014eb84b1dd70330d61b954761892bfacf))
* Support `power_on_behavior` for Gledopto GL-B-007P. https://github.com/Koenkk/zigbee2mqtt/issues/17970 ([4cbe8f7](https://github.com/Koenkk/zigbee-herdsman-converters/commit/4cbe8f7cf098e046a4ddaf9398c1c178af1bc6b6))


### Bug Fixes

* **detect:** Detect `_TZ3000_ss98ec5d` as Moes ZK-EU. https://github.com/Koenkk/zigbee2mqtt/issues/17996 ([3676845](https://github.com/Koenkk/zigbee-herdsman-converters/commit/3676845d19c8d944a230669436dd88cb5259101e))
* **detect:** Detect `_TZ3000_zw7wr5uo` as Mercator Ikuü SMI7040 ([#5870](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5870)) ([bf0e379](https://github.com/Koenkk/zigbee-herdsman-converters/commit/bf0e37924aaaf0da895c3d94e2b2aec02dfaa9c9))
* **detect:** Detect `_TZE200_nyvavzbj` as Immax 07505L. https://github.com/Koenkk/zigbee2mqtt/discussions/17973 ([ca82536](https://github.com/Koenkk/zigbee-herdsman-converters/commit/ca82536ff1bd9abf7fa7a8b27392690105c2e1c3))
* Disable OTA for Philips 9290030674 as none is available currently. https://github.com/Koenkk/zigbee2mqtt/issues/14923 ([260826c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/260826cb22d6f106993dd2a41666668ee9e1d44c))
* Disable OTA for Philips 9290030675 since non is available. https://github.com/Koenkk/zigbee2mqtt/issues/14923 ([f45cb2b](https://github.com/Koenkk/zigbee-herdsman-converters/commit/f45cb2b5d207d78ed06164b55c43adc9e1bc0b4d))
* **ignore:** Lowercase some Mercator Ikuü descriptions. https://github.com/Koenkk/zigbee-herdsman-converters/pull/5871 ([0479cbd](https://github.com/Koenkk/zigbee-herdsman-converters/commit/0479cbd4ddde11ed93fcebb016f0970269648511))
* **ignore:** update dependencies ([#5874](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5874)) ([7b1f1d8](https://github.com/Koenkk/zigbee-herdsman-converters/commit/7b1f1d8ed1935d152f8e7efc96d20b3d589d6f15))
* Normalise Mercator Ikuü vendor and device naming ([#5871](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5871)) ([f5502a7](https://github.com/Koenkk/zigbee-herdsman-converters/commit/f5502a7626aead1eb94f1430ee237fd0b3fb72fd))
* TS refactor ([d0d1832](https://github.com/Koenkk/zigbee-herdsman-converters/commit/d0d18322484b58e902734ab697b12e7a98606727))

## [15.21.2](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.21.1...v15.21.2) (2023-06-08)


### Bug Fixes

* **ignore:** Fix 0d0ceb2631ff65379ddbd7a99591453558741b4c ([7c03d14](https://github.com/Koenkk/zigbee-herdsman-converters/commit/7c03d14745b289bd8b56c9e08e69d5948644943b))

## [15.21.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.21.0...v15.21.1) (2023-06-08)


### Bug Fixes

* **ignore:** Fix exports ([0d0ceb2](https://github.com/Koenkk/zigbee-herdsman-converters/commit/0d0ceb2631ff65379ddbd7a99591453558741b4c))

## [15.21.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.20.0...v15.21.0) (2023-06-08)


### Features

* **add:** D077-ZG https://github.com/Koenkk/zigbee-herdsman-converters/issues/5859 ([c66dc5f](https://github.com/Koenkk/zigbee-herdsman-converters/commit/c66dc5fa847474f4af3d97650479925206c1be3f))
* **add:** OFL 122 C https://github.com/Koenkk/zigbee2mqtt/issues/17965 ([80725bd](https://github.com/Koenkk/zigbee-herdsman-converters/commit/80725bde8c4cf486edc606a19e1d6fec7169823b))
* **add:** ZNQBKG24LM ([#5863](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5863)) ([55731de](https://github.com/Koenkk/zigbee-herdsman-converters/commit/55731defe6820bbedc077c4391d3f25af1c872b2))
* **detect:** Detect `_TZ3000_lepzuhto` as EARU EAKCB-T-M-Z ([#5864](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5864)) ([9db91c5](https://github.com/Koenkk/zigbee-herdsman-converters/commit/9db91c5f291d352bd87c6a570ab25481e1e72447))


### Bug Fixes

* Disable unsupported `power_on_behavior` for LEDVANCE 4058075729322 @GerdRuetten  https://github.com/Koenkk/zigbee2mqtt.io/pull/2078 ([7047c6b](https://github.com/Koenkk/zigbee-herdsman-converters/commit/7047c6bb74c3adde468aff6dd8da2df6eb4f317d))
* Fix Ubisys C4, D1, J1, R0, S2 and S1-R latest OTA not available @WhistleMaster  https://github.com/Koenkk/zigbee-OTA/pull/317 ([7e5aef0](https://github.com/Koenkk/zigbee-herdsman-converters/commit/7e5aef02105533f2242c0372b1006ba0de0fa2d4))
* **ignore:** TS refactor ([62f09d4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/62f09d4592a4e9f38874eba217560bad6cb6412e))
* **ignore:** TS refactor ([#5850](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5850)) ([0c3f1b9](https://github.com/Koenkk/zigbee-herdsman-converters/commit/0c3f1b9f3fb45fb6e3c24b97b7765245238e11ac))

## [15.20.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.19.1...v15.20.0) (2023-06-08)


### Features

* **add:** 929002401001 ([#5854](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5854)) ([d294d0a](https://github.com/Koenkk/zigbee-herdsman-converters/commit/d294d0aba2fcfc6483c8bb813e878f4229164d5d))
* **add:** 948.47 [@fsedarkalex](https://github.com/fsedarkalex) https://github.com/Koenkk/zigbee2mqtt/issues/17933 ([9e98fa6](https://github.com/Koenkk/zigbee-herdsman-converters/commit/9e98fa6795cd95deadceb3c6aa21f21957748425))
* **add:** 99099 ([#5853](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5853)) ([1bf3f61](https://github.com/Koenkk/zigbee-herdsman-converters/commit/1bf3f6118f5b309e358ed309aee7915eda41d5dc))
* **detect:** Detect `SM323` as Samotech SM323. https://github.com/Koenkk/zigbee2mqtt/issues/17937 ([03f8046](https://github.com/Koenkk/zigbee-herdsman-converters/commit/03f804694814d94e01f37b4973e16a6b9326c5d1))
* Expose power per phase and add desriptions for TuYa TS0601_rcbo ([#5856](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5856)) ([beee574](https://github.com/Koenkk/zigbee-herdsman-converters/commit/beee574e08cebbe9a08563a905f2153dd727005b))


### Bug Fixes

* Fix strange "Â" in device description and unit. https://github.com/Koenkk/zigbee-herdsman-converters/issues/5857 ([e662c7b](https://github.com/Koenkk/zigbee-herdsman-converters/commit/e662c7b747a025f8c91c43d34bb0f4e6c1dbca90))
* **ignore:** Fix axis reporting for 3RVS01031Z ([#5858](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5858)) ([12a6213](https://github.com/Koenkk/zigbee-herdsman-converters/commit/12a621320e2ad5805236146ef5b20eb02e648e32))
* **ignore:** Fix errors in Xiaomi converters. https://github.com/Koenkk/zigbee2mqtt/issues/17952 ([65e0602](https://github.com/Koenkk/zigbee-herdsman-converters/commit/65e060265216ab26d68a6e6553a401638213116f))
* update changelog ([f054270](https://github.com/Koenkk/zigbee-herdsman-converters/commit/f054270576cfcd06944b208528f4df65207c0428))

## [15.19.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.19.0...v15.19.1) (2023-06-07)


### Bug Fixes

* Fix type imports ([aa5ad41](https://github.com/Koenkk/zigbee-herdsman-converters/commit/aa5ad41f643db6c7abad3415ca2fbdf501cfd6d2))
* **ignore:** Fix exports ([fceae62](https://github.com/Koenkk/zigbee-herdsman-converters/commit/fceae624a37b55719c1d2f475b90a6187a8d2809))

## [15.19.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.18.0...v15.19.0) (2023-06-07)


### Features

* **add:** 12226 [@fsedarkalex](https://github.com/fsedarkalex) https://github.com/Koenkk/zigbee2mqtt/issues/17932 ([85bedb2](https://github.com/Koenkk/zigbee-herdsman-converters/commit/85bedb2aaa46946170dfbbdf3d0196f4c2a16798))
* **add:** 948.47 [@fsedarkalex](https://github.com/fsedarkalex) https://github.com/Koenkk/zigbee2mqtt/issues/17933 ([dd9c620](https://github.com/Koenkk/zigbee-herdsman-converters/commit/dd9c6202fd36b9aae0862178740e1a97cde312da))
* **detect:** Detect `_TZ3000_nnwehhst` as TuYa TS0003_switch_module_1 [@mersadk](https://github.com/mersadk) https://github.com/Koenkk/zigbee2mqtt/issues/17928 ([ba9c117](https://github.com/Koenkk/zigbee-herdsman-converters/commit/ba9c11798d6c7c54df2d458187d1dd3a6af7eabc))
* **detect:** Detect `_TZE200_bjzrowv2` as TuYa TS0601_cover_1 ([#5851](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5851)) ([4846e14](https://github.com/Koenkk/zigbee-herdsman-converters/commit/4846e14b33470d90ad055415f8b56464abc0cf1d))
* **detect:** Detect `RDM003` as Philips 8718699693985 ([#5849](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5849)) ([2f5a7dd](https://github.com/Koenkk/zigbee-herdsman-converters/commit/2f5a7dde51be43cc0f1314476cc211d0f1f2d1be))
* Expose `MOTDETAT` for Lixee ZiPulses ([#5848](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5848)) ([d2268ae](https://github.com/Koenkk/zigbee-herdsman-converters/commit/d2268aeb13d7d94ec8addcb02603977f58d42b0d))


### Bug Fixes

* **ignore:** Fix dd9c6202fd36b9aae0862178740e1a97cde312da ([82ad852](https://github.com/Koenkk/zigbee-herdsman-converters/commit/82ad852c4217fab872e0f687ef2f6dbda088946f))
* **ignore:** TS refactor ([22bf5b2](https://github.com/Koenkk/zigbee-herdsman-converters/commit/22bf5b2edc2d136dc182131c8cac7f4d058c5579))
* **ignore:** TS refactor ([9b361c8](https://github.com/Koenkk/zigbee-herdsman-converters/commit/9b361c8742d56d3e02723f49d289ec6cd9d2d15f))
* TS refactor ([5394cfb](https://github.com/Koenkk/zigbee-herdsman-converters/commit/5394cfbd52c53a5bf7d3c8a8662662ea5722237a))
* TS refactor ([4e96286](https://github.com/Koenkk/zigbee-herdsman-converters/commit/4e962860e127229259f43915c26afb0583ff94b3))
* TS refactor ([e1f8b3c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/e1f8b3c537a99891dfb451734e52bfd2da643a20))

## [15.18.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.17.0...v15.18.0) (2023-06-05)


### Features

* **detect:** Detect `_TZE200_9cxuhakf` as Mercator Ikuü SSWM-DIMZ. https://github.com/Koenkk/zigbee2mqtt/issues/17913 ([93ea5da](https://github.com/Koenkk/zigbee-herdsman-converters/commit/93ea5da558c221eae85f4c59d7f3d76608f70a7d))
* **detect:** Detect `_TZE200_bqcqqjpb` as Yushun YS-MT750L ([#5840](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5840)) ([5f31082](https://github.com/Koenkk/zigbee-herdsman-converters/commit/5f310822db20460c7d6ee85b180cd9682928ad64))
* **detect:** Detect `_TZE200_mja3fuja` as TuYa TS0601_smart_air_house_keeper. https://github.com/Koenkk/zigbee2mqtt/issues/17439 ([994e681](https://github.com/Koenkk/zigbee-herdsman-converters/commit/994e68197cee2c0f0cd85ff4b5762d9b171859ab))


### Bug Fixes

* Disable unsupported `power_on_behaviour` for Innr FL 130 C ([#5842](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5842)) ([0de0829](https://github.com/Koenkk/zigbee-herdsman-converters/commit/0de0829374afa7b8db36099f787d58e7c0606f1d))

## [15.17.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.16.0...v15.17.0) (2023-06-04)


### Features

* **detect:** Detect `_TZ3000_4rbqgcuv` as AVATTO ZWSM16-1-Zigbee https://github.com/Koenkk/zigbee2mqtt/issues/17907 ([5916a1e](https://github.com/Koenkk/zigbee-herdsman-converters/commit/5916a1e15645d5b396a884884f548ac479bdf8f5))
* **detect:** Detect `_TZ3000_mtnpt6ws` as AVATTO ZWSM16-2-Zigbee. https://github.com/Koenkk/zigbee2mqtt/issues/17902 ([cca94e4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/cca94e43516623b1b9232665fc9402042d68d9fc))


### Bug Fixes

* **ignore:** update dependencies ([#5839](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5839)) ([302153c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/302153cdd5cc6b6f293cbb7bf692819bea2c74df))

## [15.16.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.15.1...v15.16.0) (2023-06-03)


### Features

* **add:** 929003128701 https://github.com/Koenkk/zigbee2mqtt/issues/17890 ([e675f98](https://github.com/Koenkk/zigbee-herdsman-converters/commit/e675f98109264e9f10234e0cf9af72b8372d842d))
* **add:** TH-110-ZB ([#5835](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5835)) ([667a66f](https://github.com/Koenkk/zigbee-herdsman-converters/commit/667a66fa6eb754b65783f77c9a251cf445e34c0e))
* **detect:** Detect `_TZE200_nw1r9hp6` as Zemismart ZM85EL-2Z. https://github.com/Koenkk/zigbee2mqtt/issues/11251 ([636d1b4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/636d1b4705117bcc80090e2b90cbfa800678f3fb))
* **detect:** Detect `_TZE204_wbhaespm` as RTX ZCR1-40EM ([#5834](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5834)) ([eae029d](https://github.com/Koenkk/zigbee-herdsman-converters/commit/eae029d0023af7c38c6fa41e401a9c2c9a00858a))


### Bug Fixes

* Fix TuYa TS011F_1 and TS011F_4 not detected https://github.com/Koenkk/zigbee2mqtt/issues/17883 ([7452dc1](https://github.com/Koenkk/zigbee-herdsman-converters/commit/7452dc1ace5caab1d62254cf54c7bfa143634e56))

## [15.15.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.15.0...v15.15.1) (2023-06-02)


### Bug Fixes

* **ignore:** Fix getFromLookup. https://github.com/Koenkk/zigbee2mqtt/issues/17880 ([6dedb6b](https://github.com/Koenkk/zigbee-herdsman-converters/commit/6dedb6b8d8a32bacf08a7a8043e889460aa033be))
* TS refactor ([cdbca3a](https://github.com/Koenkk/zigbee-herdsman-converters/commit/cdbca3aa91cf0ce9220cb6328a840277bf281960))
* TS refactor ([d498494](https://github.com/Koenkk/zigbee-herdsman-converters/commit/d4984944a161b96a855abc59171d7abd49695db8))

## [15.15.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.14.1...v15.15.0) (2023-06-02)


### Features

* Support OTA for NodOn SIN-4-RS-20 @AlexisPolegato https://github.com/Koenkk/zigbee-OTA/pull/318 ([96f288b](https://github.com/Koenkk/zigbee-herdsman-converters/commit/96f288b37c6c2d98b795d105a2b49847c434ac47))


### Bug Fixes

* **ignore:** Fix assertNumber https://github.com/Koenkk/zigbee2mqtt/issues/17866 ([2b70550](https://github.com/Koenkk/zigbee-herdsman-converters/commit/2b70550d72675f78490bae23ace168c554f8d223))

## [15.14.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.14.0...v15.14.1) (2023-06-01)


### Bug Fixes

* **ignore:** Improve Access type check ([beadb08](https://github.com/Koenkk/zigbee-herdsman-converters/commit/beadb081d02a61930ab653c213c291a980dcbb56))

## [15.14.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.13.1...v15.14.0) (2023-06-01)


### Features

* **add:** HA-ZGMW2-E https://github.com/Koenkk/zigbee2mqtt/issues/17840 ([2842729](https://github.com/Koenkk/zigbee-herdsman-converters/commit/284272920586be98fd910157067608564fb5577b))
* **add:** ZSS-QY-SSD-A-EN ([#5827](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5827)) ([5baf7b4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/5baf7b4bbbdb89e27e99c54414b7285cbb212781))
* Make lookup commands to TuYa devices case insensitive. https://github.com/Koenkk/zigbee2mqtt/issues/17856 ([1b99bf2](https://github.com/Koenkk/zigbee-herdsman-converters/commit/1b99bf27c19749f8225acfa060ca2eaa7253da3a))


### Bug Fixes

* Align options.supportsHS with meta.supportsHueAndSaturation ([#5811](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5811)) ([e6f0399](https://github.com/Koenkk/zigbee-herdsman-converters/commit/e6f0399352bf9291399303f646c29444ae3026e2))
* **detect:** Detect `_TZE204_5toc8efa` as Moes BHT-002-GCLZB. https://github.com/Koenkk/zigbee2mqtt/issues/17857 ([facac61](https://github.com/Koenkk/zigbee-herdsman-converters/commit/facac619288228fcd8bfff05ae8e439bb94b6eb0))
* Fix HSV colors incorrect (disable gamma correction) ([#5820](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5820)) ([b91a81b](https://github.com/Koenkk/zigbee-herdsman-converters/commit/b91a81baef9cc10a655ba1af8687e913147ab7df))
* Fix TuYa TS0601_dimmer_knob `indicator_mode` ([#5830](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5830)) ([901ca75](https://github.com/Koenkk/zigbee-herdsman-converters/commit/901ca759b7bfa5bf409504f30a27c7a6bec820b9))
* **ignore:** TS refactor ([#5812](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5812)) ([ece02be](https://github.com/Koenkk/zigbee-herdsman-converters/commit/ece02be31b93040d75d030a3d637b18198555567))

## [15.13.1-hotfix.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.13.1-hotfix.0...v15.13.1-hotfix.1) (2023-06-07)


### Bug Fixes

* **ignore:** Fix 6e91fbb2947d0d272df6941092b490c2fcf6d5bc ([df01d07](https://github.com/Koenkk/zigbee-herdsman-converters/commit/df01d077a944f139039054add18aeb08f68f252a))

## [15.13.1-hotfix.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.13.1...v15.13.1-hotfix.0) (2023-06-07)


### Bug Fixes

* Fix occupancy detection not working for TuYa TS0202 (`_TZ3040_bb6xaihh`). https://github.com/Koenkk/zigbee2mqtt/issues/17364 ([6538217](https://github.com/Koenkk/zigbee-herdsman-converters/commit/6538217f642f0820aa6158087d6e6caca41cf922))
* Fix incorrect actions for TuYa TS0044. https://github.com/Koenkk/zigbee2mqtt/issues/17862 ([6e91fbb](https://github.com/Koenkk/zigbee-herdsman-converters/commit/6e91fbb2947d0d272df6941092b490c2fcf6d5bc))
* Fix IKEA E2103 battery reporting https://github.com/Koenkk/zigbee2mqtt/issues/17888 ([a60fa86](https://github.com/Koenkk/zigbee-herdsman-converters/commit/a60fa868d986e2d7aaed75cfc2b5850866ef7896))
* Fix some TuYa TS011F detected incorrectly. ([d5958a5](https://github.com/Koenkk/zigbee-herdsman-converters/commit/d5958a5d1f60938cf875fc468716634736ee29c5))
* IKEA FYRTUR and friends on fwVer &gt;= 24 have wrong checkinInterval after OTA ([#5838](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5838)) ([17a92fa](https://github.com/Koenkk/zigbee-herdsman-converters/commit/17a92fae4695fee39656b13e6fec534eae2786d4))
* Fix IKEA E2123  SYMFONISK gen2 battery % incorrect ([#5844](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5844)) ([582f76f](https://github.com/Koenkk/zigbee-herdsman-converters/commit/582f76f61866d7879c721b4076a318c8c9410110))

## [15.13.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.13.0...v15.13.1) (2023-06-01)


### Bug Fixes

* Fix ci and exports ([3c6d5df](https://github.com/Koenkk/zigbee-herdsman-converters/commit/3c6d5dffd98dac29c985abd7ad58d11fee3c65af))
* **ignore:** Fix `_TZE204_ztc6ggyl` whitelabel ([750814d](https://github.com/Koenkk/zigbee-herdsman-converters/commit/750814d8fe7b634e57341197507bf0a9882d4192))
* **ignore:** Fix °C unit ([485078c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/485078c1c550ce1c24e4896cbe58f717d1803b42))
* **ignore:** Fix tests ([a9b47b4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/a9b47b43d5e0eae3918d5aad99e8841f01be8aa6))

## [15.13.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.12.0...v15.13.0) (2023-05-31)


### Features

* **add:** GW02 ([#5818](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5818)) ([37d83d9](https://github.com/Koenkk/zigbee-herdsman-converters/commit/37d83d930b80f0e93c39c89f5686fabf7eb1756e))
* Expose `filter_age` for IKEA E2007 ([#5816](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5816)) ([39a1928](https://github.com/Koenkk/zigbee-herdsman-converters/commit/39a19280e2dba2e0bbbee3d54667c52f85b31a5d))
* Expose `x_axis`, `y_axis` and `z_axis` for Third Reality 3RVS01031Z ([#5822](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5822)) ([54218df](https://github.com/Koenkk/zigbee-herdsman-converters/commit/54218dfb735fee6c95b46dfd87a452f00b016901))


### Bug Fixes

* **detect:** Detect `_TZ3210_dse8ogfy` as Adaprox TS0001_1. https://github.com/Koenkk/zigbee2mqtt/issues/17841 ([5ac0a39](https://github.com/Koenkk/zigbee-herdsman-converters/commit/5ac0a39d1c01a6b649019a473780e764d88ac016))
* Fix missing OTA endpoint for Xiaomi SSM-U01. https://github.com/Koenkk/zigbee2mqtt/issues/17835 ([354bedc](https://github.com/Koenkk/zigbee-herdsman-converters/commit/354bedc2376d9d073d423239bb679ca8c834e16d))

## [15.12.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.11.0...v15.12.0) (2023-05-30)


### Features

* **add:** b-parasite ([#5810](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5810)) ([b1c249a](https://github.com/Koenkk/zigbee-herdsman-converters/commit/b1c249a36c116b2a6f7fd8d9d842212be41b62fa))
* Support `tamper` and `battery` for Develco WISZB-121 ([#5813](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5813)) ([fb2a454](https://github.com/Koenkk/zigbee-herdsman-converters/commit/fb2a4547d323d2a26d0fffe3b05f3b5d5346140f))
* TS refactor ([e1fa8e1](https://github.com/Koenkk/zigbee-herdsman-converters/commit/e1fa8e1b6d32c0cf78453028703c8935c799d7f3))


### Bug Fixes

* Fix missing power source of Sonoff SNZB-02D ([#5808](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5808)) ([30b2a9b](https://github.com/Koenkk/zigbee-herdsman-converters/commit/30b2a9bc038180ae8f6d63735876a5c922b2be56))
* Fix occupancy detection not working for TuYa TS0202 (`_TZ3040_bb6xaihh`). https://github.com/Koenkk/zigbee2mqtt/issues/17364 ([6538217](https://github.com/Koenkk/zigbee-herdsman-converters/commit/6538217f642f0820aa6158087d6e6caca41cf922))
* **ignore:** Export Lock class ([#5814](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5814)) ([0a8161f](https://github.com/Koenkk/zigbee-herdsman-converters/commit/0a8161f146c99c222fb14077894f70e6c57f8050))
* **ignore:** fix 1409e99e975144187b9ea58eadbf9de6a8fec95c ([4649dcc](https://github.com/Koenkk/zigbee-herdsman-converters/commit/4649dccd59a1319fd8c0c81420fcb0491a9c52a3))
* **ignore:** fix minor comment typo in src/lib/light.js ([#5809](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5809)) ([0ef8e51](https://github.com/Koenkk/zigbee-herdsman-converters/commit/0ef8e51a8b64d9256a37c59f24c9ecbd3b92e6ed))
* **ignore:** Fix TAFFETAS2 model ID ([#5815](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5815)) ([3fd3bc4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/3fd3bc4d32335f9474f36f2fdfdf51acfa01d2a8))
* **ignore:** TS refactor ([7d98618](https://github.com/Koenkk/zigbee-herdsman-converters/commit/7d98618204f2288fc4cbb07d091305f8a5921fe7))
* **ignore:** update dependencies ([#5807](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5807)) ([13bc7c4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/13bc7c45dc28fc07f07707b665ad19793c261a42))

## [15.11.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.10.0...v15.11.0) (2023-05-27)


### Features

* **add:** 1402769 https://github.com/Koenkk/zigbee-herdsman-converters/issues/5766 ([5735246](https://github.com/Koenkk/zigbee-herdsman-converters/commit/5735246aea06e8266e7bc491ca30ad02ab73fdad))
* **add:** MC-02 ([#5799](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5799)) ([87b196c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/87b196cbc2e206c31959709e09298db3f34440c9))
* Support `power_on_behavior` and `switch_type` for TuYa TS110E_1gang_1 [@reyko01](https://github.com/reyko01)  https://github.com/Koenkk/zigbee2mqtt/issues/15372 ([fb7c604](https://github.com/Koenkk/zigbee-herdsman-converters/commit/fb7c6045a2117f7176ceaad034b88706c350cc43))
* **ignore:** TS refactor ([#5804](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5804)) ([1b6d940](https://github.com/Koenkk/zigbee-herdsman-converters/commit/1b6d940c14e73c99dad328aad3b6618f2471a917))

## [15.10.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.9.0...v15.10.0) (2023-05-26)


### Features

* **add:** LDSENK02S ([#5803](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5803)) ([cad4c52](https://github.com/Koenkk/zigbee-herdsman-converters/commit/cad4c5299158ba1df3e97a146c95146ad535e4c4))
* **ignore:** TS refactor ([#5801](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5801)) ([d11cbe1](https://github.com/Koenkk/zigbee-herdsman-converters/commit/d11cbe137e5fb4d0e6d8eabdb7eba5064409b8e5))


### Bug Fixes

* **ignore:** fix trailing space in SNZB-02P description ([#5800](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5800)) ([5900bf0](https://github.com/Koenkk/zigbee-herdsman-converters/commit/5900bf0001ae0f3218c87488944b874aeb0f8c39))

## [15.9.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.8.2...v15.9.0) (2023-05-25)


### Features

* **add:** SNZB-01P, SNZB-02P, SNZB-04P ([#5796](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5796)) ([c6f590e](https://github.com/Koenkk/zigbee-herdsman-converters/commit/c6f590e7c3df3f9f9b72eea28924b78f5228241d))
* Support OTA for Develco WISZB-120 [@ultrabug](https://github.com/ultrabug) https://github.com/Koenkk/zigbee-OTA/pull/311 ([4b84aff](https://github.com/Koenkk/zigbee-herdsman-converters/commit/4b84aff3562fc801719d9e03f37fe31b7a99dcd1))


### Bug Fixes

* Fix BTicino K4027C/L4027C/N4027C/NT4027C not updating state. https://github.com/Koenkk/zigbee2mqtt/issues/17785 ([49aff15](https://github.com/Koenkk/zigbee-herdsman-converters/commit/49aff1525c2033bdad4bbcb79828dbfbd32c4921))

## [15.8.2](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.8.1...v15.8.2) (2023-05-24)


### Bug Fixes

* **ignore:** ci.yml ([e7c1d90](https://github.com/Koenkk/zigbee-herdsman-converters/commit/e7c1d90e2826fc88354df66872ff978571347d61))

## [15.8.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.8.0...v15.8.1) (2023-05-24)


### Bug Fixes

* **ignore:** fix ci.yml ([38cda3a](https://github.com/Koenkk/zigbee-herdsman-converters/commit/38cda3afa354620fc2888bc65d5f764a7f6ffa8e))

## [15.8.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.7.1...v15.8.0) (2023-05-24)


### Features

* **add:** 9135 [@anharald](https://github.com/anharald) https://github.com/Koenkk/zigbee2mqtt/issues/17786 ([16ba1db](https://github.com/Koenkk/zigbee-herdsman-converters/commit/16ba1db909eb78b0c3c1e1e1403294c019432ab8))
* **add:** S902M-ZG https://github.com/Koenkk/zigbee2mqtt/issues/14733 ([2b45558](https://github.com/Koenkk/zigbee-herdsman-converters/commit/2b45558cebb255d339573149ee630d677a8cf7fc))
* **add:** SM0202 https://github.com/Koenkk/zigbee2mqtt/issues/15772 ([fcb9c1e](https://github.com/Koenkk/zigbee-herdsman-converters/commit/fcb9c1e5d93f9f550c16e542e945a74c2fac5272))
* Improvements for Custom devices (DiY) ptvo.info ([#5792](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5792)) ([6f2b2bc](https://github.com/Koenkk/zigbee-herdsman-converters/commit/6f2b2bc904e668103acc9b6b9f67699e6c556553))

## [15.7.1](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.7.0...v15.7.1) (2023-05-24)


### Bug Fixes

* **add:** T2106 ([#5789](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5789)) ([3b2082c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/3b2082c0ad159f193afe4261d989c162ac96156b))
* **detect:** Detect `SV01-412-MP-1.3` as Keen Home SV01 ([#5787](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5787)) ([fdaa6a4](https://github.com/Koenkk/zigbee-herdsman-converters/commit/fdaa6a41641d16c07e593bbe571f6939ac3f7f21))
* **ignore:** fix update_dependencies.yml ([8d82943](https://github.com/Koenkk/zigbee-herdsman-converters/commit/8d8294357907ce2ae810242cc0ecc02d8c622116))
* **ignore:** improve CI setup ([595a5fd](https://github.com/Koenkk/zigbee-herdsman-converters/commit/595a5fdc9fc672b7313314db84ace4258e06c0c9))

## [15.7.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.6.0...v15.7.0) (2023-05-23)


### Features

* Log TuYa `Unhandled DP` and `NOT RECOGNIZED DP` as debug instead of warn. https://github.com/Koenkk/zigbee2mqtt/issues/17615 ([4717a6c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/4717a6c8ad9ab9b0bf62ce65c9fd277555f92745))


### Bug Fixes

* **add:** GL-SD-003P https://github.com/Koenkk/zigbee2mqtt/issues/17773 ([ade80ab](https://github.com/Koenkk/zigbee-herdsman-converters/commit/ade80abd29dfea8c7209689950d344165e282f4b))
* **detect:** Detect `_TYZB01_sqmd19i1` as TuYa TS0207_water_leak_detector_3. https://github.com/Koenkk/zigbee2mqtt/issues/17763 ([844c712](https://github.com/Koenkk/zigbee-herdsman-converters/commit/844c712a5275621926e2937da866548a1e8ea5f3))
* **detect:** Detect `_TZ3000_ocjlo4ea` as TuYa TS0207_water_leak_detector_1. https://github.com/Koenkk/zigbee2mqtt/issues/17761 ([ab00fbb](https://github.com/Koenkk/zigbee-herdsman-converters/commit/ab00fbb43b35a7d51f810bc235ed00de380c96d2))
* **detect:** Detect `_TZ3000_upgcbody` as TuYa `TS0207_water_leak_detector_2`. https://github.com/Koenkk/zigbee2mqtt/issues/17762 ([82cdaf5](https://github.com/Koenkk/zigbee-herdsman-converters/commit/82cdaf5b94770c1afdbe2d44b1ce0ae447032005))
* **detect:** Detect `_TZ3000_wbloefbf` as TuYa TS011F_switch_5_gang. https://github.com/Koenkk/zigbee2mqtt/issues/17726 ([748939c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/748939ca1fceef635ecc28194591c29f0a9a68e8))
* **detect:** Detect `_TZ3210_it1u8ahz` as TuYa TS0505B_1_2. https://github.com/Koenkk/zigbee2mqtt/issues/17759 ([f77f831](https://github.com/Koenkk/zigbee-herdsman-converters/commit/f77f831897db41b68abb0e09ccfd964017ff1345))
* **detect:** Detect `_TZE204_cjbofhxw` as TuYa PJ-MGW1203 https://github.com/Koenkk/zigbee2mqtt/issues/17637 ([f2303f2](https://github.com/Koenkk/zigbee-herdsman-converters/commit/f2303f280017e4cf72fdd5a23e131dc2873c76f5))
* Fix `voltage`, `power` and `current` readings of TuYa TS011F_plug. https://github.com/Koenkk/zigbee2mqtt/issues/16709 ([8d8cc09](https://github.com/Koenkk/zigbee-herdsman-converters/commit/8d8cc09250b729760859a66bdd118ca5ad14d76c))
* **ignore:** Fix 4717a6c8ad9ab9b0bf62ce65c9fd277555f92745 ([fd883af](https://github.com/Koenkk/zigbee-herdsman-converters/commit/fd883af9cf1f131cca01eb2b0e08e3962818e4d3))

## [15.6.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.5.0...v15.6.0) (2023-05-23)


### Features

* Support `illuminance_lux ` for Xiaomi ZNCLBL01LM ([#5781](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5781)) ([1710dbc](https://github.com/Koenkk/zigbee-herdsman-converters/commit/1710dbc35e20f07d1a743f00a6f2269b692637a9))

## [15.5.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.4.0...v15.5.0) (2023-05-22)


### Features

* **detect:** Detect `_TZ3000_l6iqph4f` as Lonsonho TS130F_dual. https://github.com/Koenkk/zigbee2mqtt/issues/17753 ([57af54c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/57af54ca8cfe0b5f34dd6fa1b911ec514f50d5f8))

## [15.4.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.3.0...v15.4.0) (2023-05-22)


### Features

* **add:** 199182 ([#5768](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5768)) ([81089ff](https://github.com/Koenkk/zigbee-herdsman-converters/commit/81089ff51df4f33db2b15e7ba0b926a3027cfb58))

## [15.3.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.2.0...v15.3.0) (2023-05-22)


### Features

* **detect:** Detect `_TZ3000_eei0ubpy` as TuYa TS0002_switch_module. https://github.com/Koenkk/zigbee2mqtt/issues/17752 ([0e61bac](https://github.com/Koenkk/zigbee-herdsman-converters/commit/0e61bace69791e6bb5ebefed990fd87c6619c80b))

## [15.2.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.1.0...v15.2.0) (2023-05-22)


### Features

* Support more features for Acova TAFFETAS2 ([#5773](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5773)) ([965eb3c](https://github.com/Koenkk/zigbee-herdsman-converters/commit/965eb3c2edeb0427f1de788932971dc95ac7eda3))

## [15.1.0](https://github.com/Koenkk/zigbee-herdsman-converters/compare/v15.0.117...v15.1.0) (2023-05-22)


### Features

* **add:** HSE2936T ([#5772](https://github.com/Koenkk/zigbee-herdsman-converters/issues/5772)) ([2342194](https://github.com/Koenkk/zigbee-herdsman-converters/commit/23421941b103eede5c8351ba5a61ae04fec034bf))