# Changelog

## 1.0.0 (2025-04-29)

Full Changelog: [v0.0.1-alpha.0...v1.0.0](https://github.com/XTurbo07/bot/compare/v0.0.1-alpha.0...v1.0.0)

### Features

* add SKIP_BREW env var to ./scripts/bootstrap ([#12](https://github.com/XTurbo07/bot/issues/12)) ([6d9cb30](https://github.com/XTurbo07/bot/commit/6d9cb306b8c5a64550adad22e741ffda9d54e3cc))
* **client:** accept RFC6838 JSON content types ([#13](https://github.com/XTurbo07/bot/issues/13)) ([6e6b014](https://github.com/XTurbo07/bot/commit/6e6b0144ba4c68231860e5f2970a3f940c7d48be))
* **client:** improve logging ([01d6162](https://github.com/XTurbo07/bot/commit/01d6162b5cd98644f0471da0ac4d25bb4d5454c2))


### Bug Fixes

* **api:** improve type resolution when importing as a package ([#23](https://github.com/XTurbo07/bot/issues/23)) ([07d6ab4](https://github.com/XTurbo07/bot/commit/07d6ab4cde48bf7cf327fec81897adaa1dfcbd1a))
* **client:** fix TypeError with undefined File ([#7](https://github.com/XTurbo07/bot/issues/7)) ([0a07cae](https://github.com/XTurbo07/bot/commit/0a07cae1a00770c6038f233ed7ac7be02a5524ec))
* **client:** mark some request bodies as optional ([1cd0ba2](https://github.com/XTurbo07/bot/commit/1cd0ba2693511aa81657e93a63d0b49b564b0b5d))
* **client:** send `X-Stainless-Timeout` in seconds ([#21](https://github.com/XTurbo07/bot/issues/21)) ([4887e3b](https://github.com/XTurbo07/bot/commit/4887e3b6622db3fcccd2af9b92e88075cd5cc0ce))
* **client:** send all configured auth headers ([#26](https://github.com/XTurbo07/bot/issues/26)) ([1d394a9](https://github.com/XTurbo07/bot/commit/1d394a967ccbcb4186fb3631ec8e57dac927fb41))
* **exports:** ensure resource imports don't require /index ([#15](https://github.com/XTurbo07/bot/issues/15)) ([49b3fef](https://github.com/XTurbo07/bot/commit/49b3fef877e8a5277a43cc00277b37294e865777))
* **internal:** add mts file + crypto shim types ([#16](https://github.com/XTurbo07/bot/issues/16)) ([65065ff](https://github.com/XTurbo07/bot/commit/65065ff05ecfe0aa5a45cc71183c0eb38d4e111f))
* **internal:** clean up undefined File test ([#8](https://github.com/XTurbo07/bot/issues/8)) ([0e8d80d](https://github.com/XTurbo07/bot/commit/0e8d80d0fda9f2c4144783533bc6f3b52c19dd55))
* **internal:** fix file uploads in node 18 jest ([7668328](https://github.com/XTurbo07/bot/commit/76683283a2abf85b18cae8f9a63e01014a16c7b3))
* **internal:** return in castToError instead of throwing ([390b78c](https://github.com/XTurbo07/bot/commit/390b78c801e99a504d1347baac7a4625dfe9b85a))
* **mcp:** remove unused tools.ts ([#24](https://github.com/XTurbo07/bot/issues/24)) ([237bfc9](https://github.com/XTurbo07/bot/commit/237bfc92c8cf6f67287652f8be4b18a27bc06762))
* **tests:** manually reset node:buffer File ([#9](https://github.com/XTurbo07/bot/issues/9)) ([bef4698](https://github.com/XTurbo07/bot/commit/bef4698b5f7e0563a3aeded47b5fef687d63e9f5))


### Chores

* **ci:** add timeout thresholds for CI jobs ([b54c3f4](https://github.com/XTurbo07/bot/commit/b54c3f4dbcb62eb4ad6decb27539a72c55a1178d))
* **ci:** only use depot for staging repos ([9500f22](https://github.com/XTurbo07/bot/commit/9500f22cf5e080cee764a0410b756636a05303a4))
* **client:** minor internal fixes ([bebdacc](https://github.com/XTurbo07/bot/commit/bebdacc20f0446c463d22c0b38703dcebe141b18))
* **client:** move misc public files to new `core/` directory, deprecate old paths ([#20](https://github.com/XTurbo07/bot/issues/20)) ([97df63f](https://github.com/XTurbo07/bot/commit/97df63f9bd8dc0907d56e03a7bc06e9a9d8b076c))
* **client:** only accept standard types for file uploads ([#4](https://github.com/XTurbo07/bot/issues/4)) ([db2d330](https://github.com/XTurbo07/bot/commit/db2d330158fbefb4753fac397306594cc71edbdb))
* **docs:** improve docs for withResponse/asResponse ([#11](https://github.com/XTurbo07/bot/issues/11)) ([1faea2c](https://github.com/XTurbo07/bot/commit/1faea2cea551300759b2b17eba2b0c869ba0eb6c))
* **exports:** cleaner resource index imports ([#18](https://github.com/XTurbo07/bot/issues/18)) ([f3dd5d0](https://github.com/XTurbo07/bot/commit/f3dd5d0f998237c660cf41a8f455e21ceca1bbc0))
* **exports:** stop using path fallbacks ([#19](https://github.com/XTurbo07/bot/issues/19)) ([122308e](https://github.com/XTurbo07/bot/commit/122308ebd42701eaedab31620588a7d4ec7fa7aa))
* go live ([#1](https://github.com/XTurbo07/bot/issues/1)) ([60dd5cc](https://github.com/XTurbo07/bot/commit/60dd5cc90e78015bb7a11138bd92ef1155301431))
* **internal:** add aliases for Record and Array ([#22](https://github.com/XTurbo07/bot/issues/22)) ([bfd8d4a](https://github.com/XTurbo07/bot/commit/bfd8d4a08a525bcc819dbc7b851e31b8864de9c6))
* **internal:** codegen related update ([3db0cf6](https://github.com/XTurbo07/bot/commit/3db0cf6ca8fc47516a648ff7cd910a5289185bd0))
* **internal:** codegen related update ([645f1da](https://github.com/XTurbo07/bot/commit/645f1da980fab3ee9ae86b154b270778dbb49f96))
* **internal:** constrain synckit dev dependency ([#6](https://github.com/XTurbo07/bot/issues/6)) ([296364c](https://github.com/XTurbo07/bot/commit/296364c997a72817f5bd12e0f52c2b517b748df3))
* **internal:** fix devcontainers setup ([4500365](https://github.com/XTurbo07/bot/commit/450036547873209c6df96cec077f3bf6b586a4b8))
* **internal:** fix tests failing on node v18 ([#5](https://github.com/XTurbo07/bot/issues/5)) ([006fffc](https://github.com/XTurbo07/bot/commit/006fffc0abbceffc591d1028cb34ace1a4b9e844))
* **internal:** fix tests not always being type checked ([bb1c2ae](https://github.com/XTurbo07/bot/commit/bb1c2ae021ebd51911b8f75b3b0fc1846e6c6035))
* **internal:** improve node 18 shims ([c6fc839](https://github.com/XTurbo07/bot/commit/c6fc839f8a8ca2a6122b9dace9c0a771ec735af7))
* **internal:** minor client file refactoring ([#17](https://github.com/XTurbo07/bot/issues/17)) ([5ac7d8b](https://github.com/XTurbo07/bot/commit/5ac7d8be5a2c8e391725e1b4911b33c25014372a))
* **internal:** reduce CI branch coverage ([6c24036](https://github.com/XTurbo07/bot/commit/6c24036387c85bba511ba74f6e2adc58fbd4d7db))
* **internal:** refactor utils ([f0ab09b](https://github.com/XTurbo07/bot/commit/f0ab09b5677526a474e959b47978c2d3e65018b1))
* **internal:** remove extra empty newlines ([#14](https://github.com/XTurbo07/bot/issues/14)) ([a19ffab](https://github.com/XTurbo07/bot/commit/a19ffab8805e3fda78e05fe4cb43678178a87318))
* **internal:** remove unnecessary todo ([744189e](https://github.com/XTurbo07/bot/commit/744189e867d71dfdc551a699e6df7ec14c423b0b))
* **internal:** upload builds and expand CI branch coverage ([46e8a81](https://github.com/XTurbo07/bot/commit/46e8a817c53e8048d7ea16e30f41e1a81d6235b9))
* **perf:** faster base64 decoding ([4f21204](https://github.com/XTurbo07/bot/commit/4f212043d8ec4774d0ee0517afcf80ceb6833c2d))
* **tests:** improve enum examples ([#27](https://github.com/XTurbo07/bot/issues/27)) ([ac5b3fe](https://github.com/XTurbo07/bot/commit/ac5b3feb5423b26ea19b412d39657cc5cef6dd80))
* **types:** improved go to definition on fetchOptions ([#10](https://github.com/XTurbo07/bot/issues/10)) ([95484f7](https://github.com/XTurbo07/bot/commit/95484f7676ec83a20dda4003bb78bc014e01b4f8))
* update SDK settings ([#3](https://github.com/XTurbo07/bot/issues/3)) ([9ace2a0](https://github.com/XTurbo07/bot/commit/9ace2a0cc2e1d6ad8b16e279e9775f20ce86c9cd))


### Documentation

* swap examples used in readme ([#25](https://github.com/XTurbo07/bot/issues/25)) ([803fda1](https://github.com/XTurbo07/bot/commit/803fda198cf07dacfafacf1d9886f117233fdad1))
* update URLs from stainlessapi.com to stainless.com ([15e93ff](https://github.com/XTurbo07/bot/commit/15e93ff973cd27e1da6eb93db5c654240c5c259f))
