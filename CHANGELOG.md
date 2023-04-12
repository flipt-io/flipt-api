# Changelog

## [0.2.0](https://github.com/flipt-io/flipt-api/compare/0.1.9...0.2.0) (2023-04-12)


### ⚠ BREAKING CHANGES

* **api:** drop all non-namespaced routes

### Features

* **api:** add namespaced constraints endpoints ([b795cc8](https://github.com/flipt-io/flipt-api/commit/b795cc8314491121528049eb2effaedf7df0aa4b))
* **api:** add namespaced distributions endpoints ([21ce384](https://github.com/flipt-io/flipt-api/commit/21ce38494dd6347958058b759a2a0e5f80bcabca))
* **api:** add namespaced evaluation endpoints ([2936ca7](https://github.com/flipt-io/flipt-api/commit/2936ca7bbaf790b5f20dd84fcb0411f0ccd7847c))
* **api:** add namespaced flags endpoints ([3ccb01f](https://github.com/flipt-io/flipt-api/commit/3ccb01f456ec58cad55e64811539854361166964))
* **api:** add namespaced rules endpoints ([7972613](https://github.com/flipt-io/flipt-api/commit/7972613149e00d0eaab6fe85addac09d4b6f4fee))
* **api:** add namespaced segments endpoints ([31ed4d2](https://github.com/flipt-io/flipt-api/commit/31ed4d2f156d6435306275a6d5691b86e5b3245e))
* **api:** add namespaced variants endpoints ([2e012cd](https://github.com/flipt-io/flipt-api/commit/2e012cd8fb6301db86a6a5165d14e0306d24872f))


### Bug Fixes

* **api:** rename request types to be prefixed with namespaced ([8bc5aff](https://github.com/flipt-io/flipt-api/commit/8bc5affea15509d2c99a1d14f863976d22853ea8))


### Code Refactoring

* **api:** drop all non-namespaced routes ([0be94de](https://github.com/flipt-io/flipt-api/commit/0be94de17b4192fc96dea92b922c486ed8c615bc))

## [0.1.9](https://github.com/flipt-io/flipt-api/compare/0.1.8...0.1.9) (2023-02-22)


### Features

* **auth:** add OIDC and Kubernetes definitions to API docs ([#45](https://github.com/flipt-io/flipt-api/issues/45)) ([68d569e](https://github.com/flipt-io/flipt-api/commit/68d569e63553dde29e327ed529e4281eb7efb0cf))

## [0.1.8](https://github.com/flipt-io/flipt-api/compare/0.1.7...0.1.8) (2023-01-23)


### Features

* add expire self endpoint def ([#43](https://github.com/flipt-io/flipt-api/issues/43)) ([6637b02](https://github.com/flipt-io/flipt-api/commit/6637b022eaf7b6b0568c0942993a3b3ac53c925f))

## [0.1.7](https://github.com/flipt-io/flipt-api/compare/0.1.6...0.1.7) (2023-01-08)


### Miscellaneous Chores

* release 0.1.7 ([77971b7](https://github.com/flipt-io/flipt-api/commit/77971b7c21fdadda5e80ba4fb4f59574c859b129))

## [0.1.6](https://github.com/flipt-io/flipt-api/compare/0.1.5...0.1.6) (2022-12-21)


### Bug Fixes

* fix eval context in request; upgrade fern ([#39](https://github.com/flipt-io/flipt-api/issues/39)) ([b9e39d9](https://github.com/flipt-io/flipt-api/commit/b9e39d943450a3bc3bee6f8d4c01740ca1ea154c))

## [0.1.5](https://github.com/flipt-io/flipt-api/compare/0.1.4...0.1.5) (2022-12-12)


### Bug Fixes

* fix eval reason, not reasons ([#37](https://github.com/flipt-io/flipt-api/issues/37)) ([e12f98a](https://github.com/flipt-io/flipt-api/commit/e12f98a400e9291f60f8874b7d65fe997403a74c))

## [0.1.4](https://github.com/flipt-io/flipt-api/compare/0.1.3...0.1.4) (2022-12-01)


### Bug Fixes

* **api/auth:** add missing authentication key to create token response ([#34](https://github.com/flipt-io/flipt-api/issues/34)) ([9150b57](https://github.com/flipt-io/flipt-api/commit/9150b57534e59c631d4eed09d8c430168f81e800))

## [0.1.3](https://github.com/flipt-io/flipt-api/compare/0.1.2...0.1.3) (2022-11-30)


### Bug Fixes

* list query params are optional for segment list ([#31](https://github.com/flipt-io/flipt-api/issues/31)) ([68c8b21](https://github.com/flipt-io/flipt-api/commit/68c8b212ca56e3233df233b4bde578c694942f82))

## [0.1.2](https://github.com/flipt-io/flipt-api/compare/0.1.1...0.1.2) (2022-11-30)


### Bug Fixes

* remove commons.Pageable for now as mintlify doesnt support inheritance yet ([#29](https://github.com/flipt-io/flipt-api/issues/29)) ([63bd3c1](https://github.com/flipt-io/flipt-api/commit/63bd3c153b8115b260c7f5d41e1e7e7f9f8d09a6))

## [0.1.1](https://github.com/flipt-io/flipt-api/compare/0.1.0...0.1.1) (2022-11-25)


### Bug Fixes

* rm trailing slash for openapi defs ([b847ff8](https://github.com/flipt-io/flipt-api/commit/b847ff8554a9e26f62081a86f73b94f4e69990bc))

## [0.1.0](https://github.com/flipt-io/flipt-api/compare/0.0.26...0.1.0) (2022-11-21)


### Miscellaneous Chores

* release 0.1.0 ([a388390](https://github.com/flipt-io/flipt-api/commit/a388390d75278db65f612d2ba1445ad03760edf9))

## [0.0.26](https://github.com/flipt-io/flipt-api/compare/0.0.25...0.0.26) (2022-11-21)


### Bug Fixes

* remove totalCount from auths list response ([#25](https://github.com/flipt-io/flipt-api/issues/25)) ([c9a98e4](https://github.com/flipt-io/flipt-api/commit/c9a98e474ddc5fa59671324376e9ecb357c429bd))

## [0.0.25](https://github.com/flipt-io/flipt-api/compare/0.0.24...0.0.25) (2022-11-21)


### Miscellaneous Chores

* release 0.0.25 ([301da28](https://github.com/flipt-io/flipt-api/commit/301da287afb51ed202a436f7d3399bf8138c3d02))

## [0.0.24](https://github.com/flipt-io/flipt-api/compare/0.0.23...0.0.24) (2022-11-21)


### Miscellaneous Chores

* release 0.0.24 ([aa1c9e8](https://github.com/flipt-io/flipt-api/commit/aa1c9e8cd2213fc5d26a8edd25aed08a0f9914d7))

## Changelog
