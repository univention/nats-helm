# Changelog

## [0.2.0](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.1.2...v0.2.0) (2024-11-05)


### Features

* refactor users creation to allign with the new secrets configuration best-practices ([06fd989](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/06fd989ccd02d5b714bf06ed9e4fbefac769b76a))

## [0.1.2](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.1.1...v0.1.2) (2024-09-23)


### Bug Fixes

* allow extraConfig for nats ([9eabd5d](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/9eabd5d156b0a5a4cc789561f2362349c8782e6a))
* use .Values.persistence.size, drop .Values.config.jetstream.fileStore.pvc.size ([6a4e85b](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/6a4e85b2c9b3d51460002f1f7d4a55533893414c))

## [0.1.1](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.1.0...v0.1.1) (2024-08-23)


### Bug Fixes

* make affinity actually configurable ([99a6dc1](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/99a6dc1f40eabd0b11d6450040d19cbc476957cc))

## [0.1.0](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.0.2...v0.1.0) (2024-04-23)


### Features

* changes to support the refactored umbrella values in a nubus deployment ([bfb52d4](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/bfb52d4b3ab9f27663ec83c8105716e6913ea74b))

## [0.0.2](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.0.1...v0.0.2) (2024-04-17)


### Bug Fixes

* Adjust values so that "global.imageRegistry" works as intended ([4fdee68](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/4fdee68023d600302d7b502304b1e8a5fde0fbc2))
* Update common to version 2.19.1 and use the OCI repository ([3179c93](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/3179c93727066c8dbb815315345e9ca6dff1a67f))

## 0.0.1 (2024-02-23)


### Features

* initial working version ([9ae0ac5](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/9ae0ac5c027444f05f2c80cd5c32256e2c496fed))


### Bug Fixes

* remove unneeded startupProbe "enabled" key ([71bc91c](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/71bc91cc9d12131e6f0985cb81bd498a6ca8b7d7))
* remove unneeded startupProbe "enabled" key ([dc97bb2](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/dc97bb210ce75fead9f4193d40386daa53114b1e))
