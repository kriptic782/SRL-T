# [1.1.0](https://github.com/Torwent/SRL-T/compare/v1.0.11...v1.1.0) (2023-03-19)


### Bug Fixes

* regenerate changelog and add deprecated warnign to TRSBank.FindItem(): Boolean ([4feabaf](https://github.com/Torwent/SRL-T/commit/4feabafe07f7585a6d944befa9d7d599e23b275d))



## [1.0.11](https://github.com/Torwent/SRL-T/compare/v1.0.10...v1.0.11) (2023-03-17)


### Bug Fixes

* attempt to fix SRL-T docs. You can ignore this, nothing changed ([4ec939b](https://github.com/Torwent/SRL-T/commit/4ec939b327dd4d20028bb2d7f78b582e8a4111c7))



## [1.0.10](https://github.com/Torwent/SRL-T/compare/v1.0.9...v1.0.10) (2023-03-16)


### Bug Fixes

* **TRSBank:** The bank interface in SRL-T now checks for and handles the item incinerator ([288bff7](https://github.com/Torwent/SRL-T/commit/288bff7579234d3f0c5c7614b6fe1a5c9fb61193))



## [1.0.9](https://github.com/Torwent/SRL-T/compare/v1.0.8...v1.0.9) (2023-02-15)


### Bug Fixes

* **TPoint:** added new methods from 1500 ([b645324](https://github.com/Torwent/SRL-T/commit/b645324c2f4f74c8a02725ddbd1e3b9de966f9b0))



## [1.0.8](https://github.com/Torwent/SRL-T/compare/f65bc17a9d9cfb93a5b76ffa3ff072c44e92c3cf...v1.0.8) (2023-02-11)


### Bug Fixes

* added missing login message ([53b59b9](https://github.com/Torwent/SRL-T/commit/53b59b904fa4948dc54b5dd5b398fcc4eb187769))
* attempt to fix version not detected ([3d3e7d3](https://github.com/Torwent/SRL-T/commit/3d3e7d3c87b623699b986d4af012a02563f32ae6))
* ensured scrollbar is scrollable! ([2f1b192](https://github.com/Torwent/SRL-T/commit/2f1b192425d4ed9357d7a9ddee8da509d77ecd35))
* fixed an issue with T2DPointArray.Smallest() and T2DPointArray.Biggest() ([26ebd30](https://github.com/Torwent/SRL-T/commit/26ebd30251848495703fe9786176cb4fbaf57499))
* fixed issues with GameTabs.GetCurrentTab ([cd9d6f6](https://github.com/Torwent/SRL-T/commit/cd9d6f63ffa02a6a7d3914e62073ed461eb89e8a))
* force bump version ([0a1c553](https://github.com/Torwent/SRL-T/commit/0a1c55323cc259d19ef569c426caad012fb36f82))
* GlobalToRegion was not properly offset. ([2c4980e](https://github.com/Torwent/SRL-T/commit/2c4980eaa67a3f5f0d664b7cdde3dd6b74f6403f))
* Inventory.FindItems was not returning the actual slots the items were in. ([1cb1396](https://github.com/Torwent/SRL-T/commit/1cb1396ca366c4243e56fd9c7561114dc7506d0b))
* itemfinder ([36c75ef](https://github.com/Torwent/SRL-T/commit/36c75effb2c3125f19c260c19669f8b299c4a0c0))
* **itemfinder:** fixed noted items ([094b89f](https://github.com/Torwent/SRL-T/commit/094b89f3cf0356a652ffe0158f338dbb08adbdb0))
* magic tab detection ([ea19aae](https://github.com/Torwent/SRL-T/commit/ea19aae596e75c4cbf8274ed44a1612538243437))
* my SRL was renamed to SRL-T ([f2cbbb8](https://github.com/Torwent/SRL-T/commit/f2cbbb80b2a6826af695b07f241d52b858a5c213))
* remove left over debugging ([39cdf67](https://github.com/Torwent/SRL-T/commit/39cdf67af91365a1035937e5d19266d3d6fd29da))
* stop crashes from checking tabs when they are not available ([4724a18](https://github.com/Torwent/SRL-T/commit/4724a188446c9f66123af7b15b6c928fceef28ce))
* TAntiban.AdjustZoom() ([3e2cb2d](https://github.com/Torwent/SRL-T/commit/3e2cb2dc057661b177c6ca74e581be7e3f4484f1))
* TRSLogin tweaks and documentation ([5e98218](https://github.com/Torwent/SRL-T/commit/5e98218799aeebbc39e3a3eec38b7cc5830829c9))
* TRSMake fixes ([#68](https://github.com/Torwent/SRL-T/issues/68)) ([f4b1a62](https://github.com/Torwent/SRL-T/commit/f4b1a6269a0f0091de5621119d7d2437e41734be))
* typo in Antiban.OnSleeping ([7c71920](https://github.com/Torwent/SRL-T/commit/7c71920d3bd81fb3d0e97d8db1188bf2ca4003d5))
* update docs link ([e85e2fd](https://github.com/Torwent/SRL-T/commit/e85e2fdf90b960272621715c83a176b846fb9a35))
* update item-finder ([4130cf5](https://github.com/Torwent/SRL-T/commit/4130cf587705549e10fa0cb8bc604f46375a30dc))
* update remoteinput plugin ([ec1f4e9](https://github.com/Torwent/SRL-T/commit/ec1f4e93b32a664cb38b47e5cac266c22dd74a36))
* update version gh action ([3ee9b0b](https://github.com/Torwent/SRL-T/commit/3ee9b0b18a1058339966c04ce7788692cedc7b81))


* Bug fixes and minor additions (#65) ([0e9d699](https://github.com/Torwent/SRL-T/commit/0e9d69914cafa0e7089ca9eb2bd95febbb069505)), closes [#65](https://github.com/Torwent/SRL-T/issues/65)


### Features

* added version bumper to my SRL ([d7579eb](https://github.com/Torwent/SRL-T/commit/d7579eb3bc4b2430ae79e2a1ada687b05ad86cea))
* **bank:** methods to find bank tabs a item is in ([19a335b](https://github.com/Torwent/SRL-T/commit/19a335b85a7d4327f542167fff5724fd4ce56b2c))
* fixed zoom slider and added brightness slider ([f65bc17](https://github.com/Torwent/SRL-T/commit/f65bc17a9d9cfb93a5b76ffa3ff072c44e92c3cf))
* new keybindings.simba file to handle FKeys. ([8fd288d](https://github.com/Torwent/SRL-T/commit/8fd288d85da40aa2b9725ca92b033806305c653f))
* simba1500 walker backport ([54aa5e9](https://github.com/Torwent/SRL-T/commit/54aa5e986585997fd724efd629cb25df94ed492b))


### BREAKING CHANGES

* This update breaks compatibility with everything! If you update to this version, you will need to update WaspLib as well and the scripts that use them.
* This breaks compatibility with old SRL scripts that used the updated methods because what used to be passed as **roll** is not something else.
* `TRSMainScreen.ConvertDistance()` was renamed to `TRSMainScreen.NormalizeDistance()`.
				 This was renamed by Olly in Simba1500, I guess it's an optional change but I think the rename
				 makes sense and since we are breaking compatibility, might as well bring things closer to 1500
				 already so people have less headaches later.
				 We could also optionally keep both methods and mark this one as deprecated. I'll wait for your feedback.
				 P.S. The method was actually rewrotten in 1500 but was not worth backporting, so I just renamed it!

* fix: update `MainScreen.ConvertDistance()` references to `MainScreen.NormalizeDistance()`

* refactor: added `Contains` methods to equipment and inventory.

I've also left a comment on the PR after the last commit because I forgot to mention TRSBank.ContainsItem().

Anyway, this has the same reasoning. This is optional but I would like to bring the SRL1400 API closer to SRL1500 API.

Old methods are kept and marked with a comment as deprecated so there's no downside to adding this.

This also brings documentation to TRSInventory which is nice :)

* fix: added deprecated warnings

also added more docs to inventory

* fix: added delay after mouse drag release



