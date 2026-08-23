# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-08-23)

<section class="features">

### Features

-   [`24bc778`](https://github.com/stdlib-js/stdlib/commit/24bc778d5d4046b21bca6f71aa677433996d50ae) - add `float64` to namespace
-   [`1b645c2`](https://github.com/stdlib-js/stdlib/commit/1b645c26a16216567334bc25dded1f18d0680a3b) - add `fft/base/fftpack/ndarray/float64` namespace
-   [`f5cb262`](https://github.com/stdlib-js/stdlib/commit/f5cb26250ebd309d0d7bf6d3517f60aec7a651e6) - update `fft/base/fftpack/ndarray/generic` TypeScript declarations [(#14550)](https://github.com/stdlib-js/stdlib/pull/14550)
-   [`d358101`](https://github.com/stdlib-js/stdlib/commit/d358101daea6dddd283b13cd0a1d8e4604faa84f) - add `fft/base/fftpack/ndarray/float64/rffti` [(#13919)](https://github.com/stdlib-js/stdlib/pull/13919)
-   [`8cc9874`](https://github.com/stdlib-js/stdlib/commit/8cc9874730f7a11721ff73ad4f4d53f91b4e34a7) - add `cffti` to namespace
-   [`17f4077`](https://github.com/stdlib-js/stdlib/commit/17f407712b46ed4884d55b676400d460ebc7c079) - add `fft/base/fftpack/ndarray/generic/cffti` [(#13663)](https://github.com/stdlib-js/stdlib/pull/13663)
-   [`6cfafbb`](https://github.com/stdlib-js/stdlib/commit/6cfafbb810ba060ffe26c685fc7dd177aad3f053) - update `fft/base/fftpack/ndarray/generic` TypeScript declarations [(#14461)](https://github.com/stdlib-js/stdlib/pull/14461)
-   [`1fadbac`](https://github.com/stdlib-js/stdlib/commit/1fadbacd16ab714985abb759fcb3989f16b5dc16) - add `fft/base/fftpack/ndarray` namespace
-   [`c6ce075`](https://github.com/stdlib-js/stdlib/commit/c6ce075e8de00c48d1d6f54c51da806ab7004490) - add `fft/base/fftpack/ndarray/generic` namespace
-   [`bec7095`](https://github.com/stdlib-js/stdlib/commit/bec70958b3da7b89f5bd3c3a56bb1237898c504e) - add `fft/base/fftpack/ndarray/generic/rffti`
-   [`c0b901f`](https://github.com/stdlib-js/stdlib/commit/c0b901f2aa61b6b7a56c24be582cf8da59a67b99) - add `fft/base/fftpack/ndarray/rffti` [(#13527)](https://github.com/stdlib-js/stdlib/pull/13527)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`4c7e8a1`](https://github.com/stdlib-js/stdlib/commit/4c7e8a1314064e7740e694ef6f7dbc29a78a4e91): remove `fft/base/fftpack/ndarray/rffti`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/fft-base/fftpack/ndarray/generic/rffti` which provides the same API and implementation.
        Ref: https://github.com/stdlib-js/metr-issue-tracker/issues/1165

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`24bc778`](https://github.com/stdlib-js/stdlib/commit/24bc778d5d4046b21bca6f71aa677433996d50ae) - **feat:** add `float64` to namespace _(by Athan Reines)_
-   [`1b645c2`](https://github.com/stdlib-js/stdlib/commit/1b645c26a16216567334bc25dded1f18d0680a3b) - **feat:** add `fft/base/fftpack/ndarray/float64` namespace _(by Athan Reines)_
-   [`86cd981`](https://github.com/stdlib-js/stdlib/commit/86cd981199dc115e9b7484131436c802c3d9a090) - **docs:** update namespace table of contents [(#14552)](https://github.com/stdlib-js/stdlib/pull/14552) _(by stdlib-bot)_
-   [`f5cb262`](https://github.com/stdlib-js/stdlib/commit/f5cb26250ebd309d0d7bf6d3517f60aec7a651e6) - **feat:** update `fft/base/fftpack/ndarray/generic` TypeScript declarations [(#14550)](https://github.com/stdlib-js/stdlib/pull/14550) _(by stdlib-bot)_
-   [`d358101`](https://github.com/stdlib-js/stdlib/commit/d358101daea6dddd283b13cd0a1d8e4604faa84f) - **feat:** add `fft/base/fftpack/ndarray/float64/rffti` [(#13919)](https://github.com/stdlib-js/stdlib/pull/13919) _(by Gunj Joshi, Athan Reines)_
-   [`8cc9874`](https://github.com/stdlib-js/stdlib/commit/8cc9874730f7a11721ff73ad4f4d53f91b4e34a7) - **feat:** add `cffti` to namespace _(by Athan Reines)_
-   [`2734bb3`](https://github.com/stdlib-js/stdlib/commit/2734bb3ac82d0174dfe502569e6902e20d4d4745) - **docs:** add missing notes [(#14528)](https://github.com/stdlib-js/stdlib/pull/14528) _(by Gunj Joshi, Athan Reines)_
-   [`17f4077`](https://github.com/stdlib-js/stdlib/commit/17f407712b46ed4884d55b676400d460ebc7c079) - **feat:** add `fft/base/fftpack/ndarray/generic/cffti` [(#13663)](https://github.com/stdlib-js/stdlib/pull/13663) _(by Gunj Joshi)_
-   [`46c4f3e`](https://github.com/stdlib-js/stdlib/commit/46c4f3e2710ae201ca82636ad4c0a2dd04711795) - **docs:** update description [(#14508)](https://github.com/stdlib-js/stdlib/pull/14508) _(by stdlib-bot)_
-   [`6cfafbb`](https://github.com/stdlib-js/stdlib/commit/6cfafbb810ba060ffe26c685fc7dd177aad3f053) - **feat:** update `fft/base/fftpack/ndarray/generic` TypeScript declarations [(#14461)](https://github.com/stdlib-js/stdlib/pull/14461) _(by stdlib-bot)_
-   [`1cc6f73`](https://github.com/stdlib-js/stdlib/commit/1cc6f7395e6b120317237eeca0c93b410038f5a8) - **docs:** update description _(by Athan Reines)_
-   [`c5d553b`](https://github.com/stdlib-js/stdlib/commit/c5d553b67e4bd6497dc2b99ee8787b54b1e3e761) - **docs:** update namespace table of contents [(#14465)](https://github.com/stdlib-js/stdlib/pull/14465) _(by stdlib-bot)_
-   [`0bb4e52`](https://github.com/stdlib-js/stdlib/commit/0bb4e5246b331085ed7828f2df71708e64156f41) - **chore:** clean-up [(#14443)](https://github.com/stdlib-js/stdlib/pull/14443) _(by Philipp Burckhardt)_
-   [`1fadbac`](https://github.com/stdlib-js/stdlib/commit/1fadbacd16ab714985abb759fcb3989f16b5dc16) - **feat:** add `fft/base/fftpack/ndarray` namespace _(by Athan Reines)_
-   [`9154a91`](https://github.com/stdlib-js/stdlib/commit/9154a91779deb48c7048b11704fe54fa2c9786d4) - **docs:** update description _(by Athan Reines)_
-   [`c6ce075`](https://github.com/stdlib-js/stdlib/commit/c6ce075e8de00c48d1d6f54c51da806ab7004490) - **feat:** add `fft/base/fftpack/ndarray/generic` namespace _(by Athan Reines)_
-   [`4c7e8a1`](https://github.com/stdlib-js/stdlib/commit/4c7e8a1314064e7740e694ef6f7dbc29a78a4e91) - **remove:** remove `fft/base/fftpack/ndarray/rffti` _(by Gunj Joshi)_
-   [`bec7095`](https://github.com/stdlib-js/stdlib/commit/bec70958b3da7b89f5bd3c3a56bb1237898c504e) - **feat:** add `fft/base/fftpack/ndarray/generic/rffti` _(by Gunj Joshi)_
-   [`8333b41`](https://github.com/stdlib-js/stdlib/commit/8333b41e13bac89b76e579b62621ef4e24557595) - **refactor:** update paths _(by Gunj Joshi)_
-   [`c0b901f`](https://github.com/stdlib-js/stdlib/commit/c0b901f2aa61b6b7a56c24be582cf8da59a67b99) - **feat:** add `fft/base/fftpack/ndarray/rffti` [(#13527)](https://github.com/stdlib-js/stdlib/pull/13527) _(by Gunj Joshi, Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 3 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gunj Joshi
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

