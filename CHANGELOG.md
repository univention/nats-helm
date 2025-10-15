# Changelog

## [0.6.0](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/compare/v0.5.0...v0.6.0) (2025-10-15)


### Features

* allow templated keymappings ([aa8c1f8](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/aa8c1f8e5eb98cec0d2310da58747d288a8f9de9)), closes [univention/dev/internal/team-nubus#1441](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1441)

## [0.5.0](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/compare/v0.4.3...v0.5.0) (2025-10-13)


### Features

* Support existingSecrets pattern for nats users and passwords ([fa4c061](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/fa4c06151e41966dae0cb254a216b98f7e40af30)), closes [univention/dev/internal/team-nubus#1399](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1399)


### Bug Fixes

* Add helm unittests for the secrets used in the chart and fix chart bugs that the unittests discovered ([308bd91](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/308bd9169fc8c975b29035eb7d0c438daf6921f3)), closes [univention/dev/internal/team-nubus#1399](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1399)
* add kyverno to pre-commit hooks ([83853f5](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/83853f5ab83419e57d9b9572ccd88ec76f72b969)), closes [univention/dev/internal/team-nubus#1399](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1399)
* Allign labels, annotations, and image configuration to the Nubus standards ([6698f9e](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/6698f9e557de19ed377e8ed595793b7a105ffa8e)), closes [univention/dev/internal/team-nubus#1399](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1399)
* Ensure that auth.existingSecret.name and auth.username can be templated ([c78753e](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/c78753e7133363e8eff7d182b59bc990794eea12)), closes [univention/dev/internal/team-nubus#1399](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1399)
* Nats container image version bump from 2.11.6 to 2.11.9 and disable the config reloader by default ([4871486](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/48714865e42fb6c90385e471d335cab7c54b5b0c)), closes [univention/dev/internal/team-nubus#1399](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1399)
* Remove unnecessary _helpers.tpl ([248e083](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/248e0830d38f005566cb56655c6ac4e34e58d8a1)), closes [univention/dev/internal/team-nubus#1399](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1399)

## [0.4.3](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/compare/v0.4.2...v0.4.3) (2025-08-14)


### Bug Fixes

* storageClass is changed to match the helm template ([8ef3543](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/8ef35437a6652638653af7e87b1abedf0583c8c6)), closes [univention/dev/internal/team-nubus#1382](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1382)

## [0.4.2](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/compare/v0.4.1...v0.4.2) (2025-07-28)


### Bug Fixes

* upgrade NATS to version 2.11.6 ([dc4a1ed](https://git.knut.univention.de/univention/dev/nubus-for-k8s/nats-helm/commit/dc4a1ed6d2695fcae6f0d702bce4d5c8875def54)), closes [univention/dev/internal/team-nubus#1350](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1350)

## [0.4.1](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.4.0...v0.4.1) (2025-05-09)


### Bug Fixes

* move addlicense pre-commit hook ([5551544](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/5551544228807b5e1c48b333d01cb04ca8f973ea))
* update common-ci to main ([ffe69d4](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/ffe69d48570e2bad70d06128420dbf3b66e5dae5))

## [0.4.0](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.3.2...v0.4.0) (2025-04-29)


### Features

* Remove docker.io dependencies ([0a2357f](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/0a2357fa16212779d50060ea13e0279810015caf)), closes [univention/dev/internal/team-nubus#1131](https://git.knut.univention.de/univention/dev/internal/team-nubus/issues/1131)

## [0.3.2](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.3.1...v0.3.2) (2025-03-15)


### Bug Fixes

* Fix image tag typo ([ac64496](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/ac64496eca95ee03fc291c50249f9aab009d5704))

## [0.3.1](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.3.0...v0.3.1) (2025-03-15)


### Bug Fixes

* Update nats container versions ([a23a041](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/a23a041143d3426e8d583641c5ea88d48205aaa5)), closes [univention/dev-issues/dev-incidents#131](https://git.knut.univention.de/univention/dev-issues/dev-incidents/issues/131)

## [0.3.0](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/compare/v0.2.0...v0.3.0) (2025-01-13)


### Features

* enable authorization by default ([c23bcf3](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/c23bcf38eea6f42071ce44556471e1ba64243b49))
* refactor users creation to allign with the new secrets configuration best-practices ([90b513f](https://git.knut.univention.de/univention/customers/dataport/upx/nats-helm/commit/90b513ff57535634950b1a43530bf754477bc5e4))

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
