# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [2.0.0-beta.0](https://github.com/hperrin/svelte-material-ui/compare/v2.0.0-alpha.0...v2.0.0-beta.0) (2021-01-01)


### Bug Fixes

* small fixes for MDC 4 ([6c0585f](https://github.com/hperrin/svelte-material-ui/commit/6c0585ffa7d861b5a632544d92f2769097a439e8))


### Features

* updated touch features for MDC 4 ([b06e851](https://github.com/hperrin/svelte-material-ui/commit/b06e851c0f8927670603e9d3f3ce4a2ce7b3e47c))





# [2.0.0-alpha.0](https://github.com/hperrin/svelte-material-ui/compare/v1.1.0...v2.0.0-alpha.0) (2020-12-31)


### Bug Fixes

* filter chip leading icon wasn't hidden correctly ([b011df9](https://github.com/hperrin/svelte-material-ui/commit/b011df92eac4956caf1ea51bedfaa7316de84ed3))
* fix buttons, ripples, and list item for new mdc ([9b902b5](https://github.com/hperrin/svelte-material-ui/commit/9b902b5def4bbdc0bbe34733a723ce1de1452bf9))
* forward events from dynamic components correctly ([5367449](https://github.com/hperrin/svelte-material-ui/commit/536744953b6f935b4ab1de75828308a90c238e83))


### Features

* update chips to work with MDC 4 ([2c28796](https://github.com/hperrin/svelte-material-ui/commit/2c2879649b72947ae0ed51fd2c2a62f6a5756dae))
* update Select to work with MDC 4 ([81a7ee9](https://github.com/hperrin/svelte-material-ui/commit/81a7ee992d968bab7e950b6ff7db2d47c7c17b79))
* updated form field related features for MDC 4 ([4894cfb](https://github.com/hperrin/svelte-material-ui/commit/4894cfb08da0a703e86a086d0bfdce76ae98d88c))


### BREAKING CHANGES

* Select has some breaking changes listed in the migration docs.
* Chips has several breaking changes listed in the migration docs.





# [1.1.0](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0...v1.1.0) (2020-12-24)


### Features

* make tab an anchor if href prop is present ([d9f800b](https://github.com/hperrin/svelte-material-ui/commit/d9f800b5311cb3d25047bd25305a2b2a6deaecc8))





# [1.0.0](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.21...v1.0.0) (2020-08-04)

**Note:** Version bump only for package svelte-material-ui





# [1.0.0-beta.21](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.20...v1.0.0-beta.21) (2020-04-19)


### Bug Fixes

* undefined current_component in browsers not supporting import [#60](https://github.com/hperrin/svelte-material-ui/issues/60) ([708abd6](https://github.com/hperrin/svelte-material-ui/commit/708abd6dda5579c2e77e741349834deca0bd4d61))





# [1.0.0-beta.20](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.19...v1.0.0-beta.20) (2020-01-31)


### Bug Fixes

* Cannot read property 'destroy' of undefined in menuSurface ([2bd8d37](https://github.com/hperrin/svelte-material-ui/commit/2bd8d37eb572211365b7aa6163036a7fd5c21c3f))
* fix button group styling in Safari/iOS ([eb52cc6](https://github.com/hperrin/svelte-material-ui/commit/eb52cc6b81011d004b5ee2d52851ca35e510a578))
* fix Svelte warning about unused class export ([baac41b](https://github.com/hperrin/svelte-material-ui/commit/baac41bc4d1893325a23a51ab23c79997ba54fe3))


### Features

* add component option to Button to allow other elements/components ([95d4d49](https://github.com/hperrin/svelte-material-ui/commit/95d4d49026f30579a888d9e2baa59785fcbe65f5))
* reduce Ripple arguments and add class forwarding option ([550ac93](https://github.com/hperrin/svelte-material-ui/commit/550ac93cc6d4dfa18eee70f6c1db55f1971cd8fc))





# [1.0.0-beta.19](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.18...v1.0.0-beta.19) (2019-12-13)


### Bug Fixes

* prevent new Svelte versions from mangling MDC classes ([8a94e95](https://github.com/hperrin/svelte-material-ui/commit/8a94e95574c36595158603c83b3d79892fe4af4d)), closes [#52](https://github.com/hperrin/svelte-material-ui/issues/52)
* stop empty attrs on elements ([084bc39](https://github.com/hperrin/svelte-material-ui/commit/084bc391e0f3e20decd1ac305aeb6a5c78c84810))


### Features

* add shape props for button to create rounded buttons ([a94cf69](https://github.com/hperrin/svelte-material-ui/commit/a94cf696d44691f5e9806b94bd1ab63db6fecd85))
* add shape props for button to create rounded buttons ([7fb3b8b](https://github.com/hperrin/svelte-material-ui/commit/7fb3b8bb1ac8f89115edba1087d297e011854910))





# [1.0.0-beta.18](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.17...v1.0.0-beta.18) (2019-11-08)


### Bug Fixes

* layout components when dialog is opened ([fee2755](https://github.com/hperrin/svelte-material-ui/commit/fee27554ee07605184c5846f7d49e0f845609618)), closes [#35](https://github.com/hperrin/svelte-material-ui/issues/35)
* remove hoisted menu-surface from body in onDestroy ([8e905b7](https://github.com/hperrin/svelte-material-ui/commit/8e905b7cf28b1bb5ddf8e88b478123532146e2b1))
* working on fixing dialog. wip ([601d4fd](https://github.com/hperrin/svelte-material-ui/commit/601d4fdc037943b58ff48bd1a05200af597b401f))





# [1.0.0-beta.17](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.16...v1.0.0-beta.17) (2019-10-28)


### Bug Fixes

* fixed initial value state of Select component ([4afdfc2](https://github.com/hperrin/svelte-material-ui/commit/4afdfc2fcb760c7acf9a486882078f2698944ec7))
* handle blank number input as NaN ([939543f](https://github.com/hperrin/svelte-material-ui/commit/939543f2a824deac29e77a912cb26cbe0dd0f2fb))


### Features

* add three line lists (modifying MintyMods code) ([5894c23](https://github.com/hperrin/svelte-material-ui/commit/5894c23f0ac18286e54ce5e80a33da2c8d1480fc))
* update MDC package versions to 3.2.0 ([605753d](https://github.com/hperrin/svelte-material-ui/commit/605753dd3fe121eba2654498f62f8ddd57a9e3b9))





# [1.0.0-beta.16](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.15...v1.0.0-beta.16) (2019-09-24)

**Note:** Version bump only for package svelte-material-ui





# [1.0.0-beta.15](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.14...v1.0.0-beta.15) (2019-09-13)


### Bug Fixes

* fixed ClassAdder components to allow SSR ([de0daa1](https://github.com/hperrin/svelte-material-ui/commit/de0daa1)), closes [#29](https://github.com/hperrin/svelte-material-ui/issues/29)
* forgot the dialog excludes ([78e6ca9](https://github.com/hperrin/svelte-material-ui/commit/78e6ca9))
* let dialog buttons be links, even though it's not MDC compliant ([e504cd7](https://github.com/hperrin/svelte-material-ui/commit/e504cd7))
* prefer direct for prop over context on floating label ([9184532](https://github.com/hperrin/svelte-material-ui/commit/9184532))





# [1.0.0-beta.14](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.13...v1.0.0-beta.14) (2019-09-07)


### Bug Fixes

* fixed more sass commands ([1c81e01](https://github.com/hperrin/svelte-material-ui/commit/1c81e01))
* fixed the packages' sass commands ([97d64ea](https://github.com/hperrin/svelte-material-ui/commit/97d64ea))





# [1.0.0-beta.13](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.12...v1.0.0-beta.13) (2019-09-06)


### Features

* add bare js and css to all components ([ebe7a6d](https://github.com/hperrin/svelte-material-ui/commit/ebe7a6d))





# [1.0.0-beta.12](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.11...v1.0.0-beta.12) (2019-09-06)


### Bug Fixes

* properly import Ripple and its styles ([9588c8b](https://github.com/hperrin/svelte-material-ui/commit/9588c8b))





# [1.0.0-beta.11](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.10...v1.0.0-beta.11) (2019-09-06)


### Bug Fixes

* allow for prop on wrapped floating label ([b69049c](https://github.com/hperrin/svelte-material-ui/commit/b69049c))
* import styles correctly ([37e6fa6](https://github.com/hperrin/svelte-material-ui/commit/37e6fa6))


### Features

* provide bare js and css (button only for test) for use in REPL ([1b9a268](https://github.com/hperrin/svelte-material-ui/commit/1b9a268))





# [1.0.0-beta.10](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.9...v1.0.0-beta.10) (2019-09-03)


### Bug Fixes

* dependencies between packages ([a883601](https://github.com/hperrin/svelte-material-ui/commit/a883601))





# [1.0.0-beta.8](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.7...v1.0.0-beta.8) (2019-08-30)

**Note:** Version bump only for package svelte-material-ui





# [1.0.0-beta.7](https://github.com/hperrin/svelte-material-ui/compare/v1.0.0-beta.6...v1.0.0-beta.7) (2019-08-29)



# 1.0.0-beta.6 (2019-08-27)

**Note:** Version bump only for package svelte-material-ui
