# [@adrian.insua/ngredux-router-v1.2.0](https://github.com/AdrianInsua/platform/compare/@adrian.insua/ngredux-router-v1.1.1...@adrian.insua/ngredux-router-v1.2.0) (2022-05-09)


### Features

* buump ng dependencies to v13 ([4246a74](https://github.com/AdrianInsua/platform/commit/4246a74be46ea6e84312a1981efc34622482f353))

# [@adrian.insua/ngredux-router-v1.1.1](https://github.com/AdrianInsua/platform/compare/@adrian.insua/ngredux-router-v1.1.0...@adrian.insua/ngredux-router-v1.1.1) (2021-10-09)


### Bug Fixes

* increase rxjs version ([e1ca41c](https://github.com/AdrianInsua/platform/commit/e1ca41cf83f21d6c2b02335ce2e99e03097db98c))

# [@adrian.insua/ngredux-router-v1.1.0](https://github.com/AdrianInsua/platform/compare/@adrian.insua/ngredux-router-v1.0.2...@adrian.insua/ngredux-router-v1.1.0) (2021-09-30)


### Features

* bump angular to v12 and compile with ivy ([0f0cbaa](https://github.com/AdrianInsua/platform/commit/0f0cbaa1977f8f93684b9c9163246f452dd1bacd))

# [@adrian.insua/ngredux-router-v1.1.0-release-candidate.1](https://github.com/AdrianInsua/platform/compare/@adrian.insua/ngredux-router-v1.0.2...@adrian.insua/ngredux-router-v1.1.0-release-candidate.1) (2021-09-29)


### Features

* bump angular to v12 and compile with ivy ([0f0cbaa](https://github.com/AdrianInsua/platform/commit/0f0cbaa1977f8f93684b9c9163246f452dd1bacd))

# [@adrian.insua/ngredux-router-v1.0.2](https://github.com/AdrianInsua/platform/compare/@adrian.insua/ngredux-router-v1.0.1...@adrian.insua/ngredux-router-v1.0.2) (2021-09-29)


### Bug Fixes

* fix build paths ([#2](https://github.com/AdrianInsua/platform/issues/2)) ([57d1cae](https://github.com/AdrianInsua/platform/commit/57d1cae0f159e91224ef563d0b2f3ceddf2fad52))

# [@adrian.insua/ngredux-router-v1.0.1](https://github.com/AdrianInsua/platform/compare/@adrian.insua/ngredux-router-v1.0.0...@adrian.insua/ngredux-router-v1.0.1) (2021-09-28)


### Bug Fixes

* fix dist routes ([#1](https://github.com/AdrianInsua/platform/issues/1)) ([c072d97](https://github.com/AdrianInsua/platform/commit/c072d97891835c717c8279acd5f66d1b4a405107))

# @adrian.insua/ngredux-router-v1.0.0 (2021-09-28)


### Bug Fixes

* change package names to be user scoped ([c0c9d1d](https://github.com/AdrianInsua/platform/commit/c0c9d1d87bc40078c5da8dd5c3ab2ffab1ccc54a))
* fix eslint ([ab4d1d3](https://github.com/AdrianInsua/platform/commit/ab4d1d335d90ecdba5df3c517fff1eb37719a13f))
* fix package linking ([56354a5](https://github.com/AdrianInsua/platform/commit/56354a51d7af9fa6b231144bdf43b744aec086f4))
* update peer dependencies from ^9.0.0 to ^10.0.0 ([#87](https://github.com/AdrianInsua/platform/issues/87)) ([fcea502](https://github.com/AdrianInsua/platform/commit/fcea502f44cff441737c51ebf539268c594e9bfa))


### chore

* **build:** use ng-packagr ([#37](https://github.com/AdrianInsua/platform/issues/37)) ([dffe23a](https://github.com/AdrianInsua/platform/commit/dffe23ade3417bdb5f58cecdf760039be771bc92)), closes [#9](https://github.com/AdrianInsua/platform/issues/9)
* **linting:** add global tslint rules ([#35](https://github.com/AdrianInsua/platform/issues/35)) ([336cc60](https://github.com/AdrianInsua/platform/commit/336cc60921119bc5f5c7d22d9a364db93fef244b)), closes [#4](https://github.com/AdrianInsua/platform/issues/4)


### Features

* add bootstraping script ([3fd7b32](https://github.com/AdrianInsua/platform/commit/3fd7b32faf69346e020eb5f991ffba47e445c243))
* bump angular version to 11.0.5 ([1b8bb72](https://github.com/AdrianInsua/platform/commit/1b8bb72a0fea50c583dc9d943dac5506a2ba0ff4))
* refactor packages to match new ng-packager ([710edef](https://github.com/AdrianInsua/platform/commit/710edefc2d23b0a731254c3af16969331036d94f))
* upgrade to angular 7 ([#72](https://github.com/AdrianInsua/platform/issues/72)) ([18d9245](https://github.com/AdrianInsua/platform/commit/18d924563618988f949c47b74d567e7c9f75e605)), closes [#65](https://github.com/AdrianInsua/platform/issues/65) [#66](https://github.com/AdrianInsua/platform/issues/66) [#67](https://github.com/AdrianInsua/platform/issues/67) [#68](https://github.com/AdrianInsua/platform/issues/68) [#69](https://github.com/AdrianInsua/platform/issues/69) [#70](https://github.com/AdrianInsua/platform/issues/70) [#71](https://github.com/AdrianInsua/platform/issues/71) [#74](https://github.com/AdrianInsua/platform/issues/74) [#79](https://github.com/AdrianInsua/platform/issues/79)


### BREAKING CHANGES

* Upgrades Angular dependencies to v7
* **build:** - changes the output to conform to the Angular Package Format. This may cause subtle differences in consumption behaviour
- peer dependencies have been corrected to actual dependencies
* **linting:** - ConnectArray has been renamed to ConnectArrayDirective
- ReactiveConnect has been renamed to ReactiveConnectDirective
- Connect has been renamed to ConnectDirective
- interfaces with an "I" prefix have had that prefix removed (e.g "IAppStore" -> "AppStore")

# ngredux-router-v1.0.0 (2021-09-28)


### Bug Fixes

* fix eslint ([ab4d1d3](https://github.com/AdrianInsua/platform/commit/ab4d1d335d90ecdba5df3c517fff1eb37719a13f))
* fix package linking ([56354a5](https://github.com/AdrianInsua/platform/commit/56354a51d7af9fa6b231144bdf43b744aec086f4))
* update peer dependencies from ^9.0.0 to ^10.0.0 ([#87](https://github.com/AdrianInsua/platform/issues/87)) ([fcea502](https://github.com/AdrianInsua/platform/commit/fcea502f44cff441737c51ebf539268c594e9bfa))


### chore

* **build:** use ng-packagr ([#37](https://github.com/AdrianInsua/platform/issues/37)) ([dffe23a](https://github.com/AdrianInsua/platform/commit/dffe23ade3417bdb5f58cecdf760039be771bc92)), closes [#9](https://github.com/AdrianInsua/platform/issues/9)
* **linting:** add global tslint rules ([#35](https://github.com/AdrianInsua/platform/issues/35)) ([336cc60](https://github.com/AdrianInsua/platform/commit/336cc60921119bc5f5c7d22d9a364db93fef244b)), closes [#4](https://github.com/AdrianInsua/platform/issues/4)


### Features

* add bootstraping script ([3fd7b32](https://github.com/AdrianInsua/platform/commit/3fd7b32faf69346e020eb5f991ffba47e445c243))
* bump angular version to 11.0.5 ([1b8bb72](https://github.com/AdrianInsua/platform/commit/1b8bb72a0fea50c583dc9d943dac5506a2ba0ff4))
* refactor packages to match new ng-packager ([710edef](https://github.com/AdrianInsua/platform/commit/710edefc2d23b0a731254c3af16969331036d94f))
* upgrade to angular 7 ([#72](https://github.com/AdrianInsua/platform/issues/72)) ([18d9245](https://github.com/AdrianInsua/platform/commit/18d924563618988f949c47b74d567e7c9f75e605)), closes [#65](https://github.com/AdrianInsua/platform/issues/65) [#66](https://github.com/AdrianInsua/platform/issues/66) [#67](https://github.com/AdrianInsua/platform/issues/67) [#68](https://github.com/AdrianInsua/platform/issues/68) [#69](https://github.com/AdrianInsua/platform/issues/69) [#70](https://github.com/AdrianInsua/platform/issues/70) [#71](https://github.com/AdrianInsua/platform/issues/71) [#74](https://github.com/AdrianInsua/platform/issues/74) [#79](https://github.com/AdrianInsua/platform/issues/79)


### BREAKING CHANGES

* Upgrades Angular dependencies to v7
* **build:** - changes the output to conform to the Angular Package Format. This may cause subtle differences in consumption behaviour
- peer dependencies have been corrected to actual dependencies
* **linting:** - ConnectArray has been renamed to ConnectArrayDirective
- ReactiveConnect has been renamed to ReactiveConnectDirective
- Connect has been renamed to ConnectDirective
- interfaces with an "I" prefix have had that prefix removed (e.g "IAppStore" -> "AppStore")

# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.
