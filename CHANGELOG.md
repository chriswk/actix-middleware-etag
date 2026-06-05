# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.6](https://github.com/Unleash/actix-middleware-etag/compare/v0.4.5...v0.4.6) - 2025-08-04

### 🚀 Features
- expose a way to enable forced strong etags ([#17](https://github.com/unleash/actix-middleware-etag/issues/17)) (by @sighphyre) - #17

### Contributors

* @sighphyre

## [0.4.5](https://github.com/Unleash/actix-middleware-etag/compare/v0.4.4...v0.4.5) - 2025-08-04

### 🚀 Features
- add an override for generating strong etags ([#14](https://github.com/unleash/actix-middleware-etag/issues/14)) (by @sighphyre) - #14

### Dependency updates
- bump actix-service from 2.0.2 to 2.0.3 ([#9](https://github.com/unleash/actix-middleware-etag/issues/9)) (by @dependabot[bot]) - #9
- bump actions/create-github-app-token from 1 to 2 ([#11](https://github.com/unleash/actix-middleware-etag/issues/11)) (by @dependabot[bot]) - #11
- bump actix-web from 4.9.0 to 4.11.0 ([#13](https://github.com/unleash/actix-middleware-etag/issues/13)) (by @dependabot[bot]) - #13

### Contributors

* @dependabot[bot]
* @sighphyre
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.4](https://github.com/Unleash/actix-middleware-etag/compare/v0.4.3...v0.4.4) - 2025-02-20

### 🚀 Features
- delta etag is strong not weak (#7) (by @sjaanus) - #7

### Contributors

* @sjaanus

## [0.4.3](https://github.com/Unleash/actix-middleware-etag/compare/v0.4.2...v0.4.3) - 2025-02-19

### 🚀 Features
- respect custom etag (#6) (by @kwasniew) - #6

### 💼 Other
- move to release-plz for release workflow (#4) (by @chriswk) - #4

### Contributors

* @kwasniew
* @chriswk

## v0.5.0 (2026-06-05)

### Chore

 - <csr-id-fabfcab61d23dd62f69c5d42a8b987bc5c3b1eba/> update dependencies

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 1 commit contributed to the release.
 - 305 days passed between releases.
 - 1 commit was understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Update dependencies ([`fabfcab`](https://github.com/chriswk/actix-middleware-etag/commit/fabfcab61d23dd62f69c5d42a8b987bc5c3b1eba))
</details>

## v0.4.6 (2025-08-04)

### Chore

 - <csr-id-b5a538684ebc592753aedcbcda8f97768261761d/> release v0.4.6

### New Features

 - <csr-id-4abf15fdd823123c5b2aa5dfe0b23dba36336c82/> expose a way to enable forced strong etags

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 2 commits contributed to the release.
 - 2 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 2 unique issues were worked on: [#17](https://github.com/chriswk/actix-middleware-etag/issues/17), [#18](https://github.com/chriswk/actix-middleware-etag/issues/18)

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **[#17](https://github.com/chriswk/actix-middleware-etag/issues/17)**
    - Expose a way to enable forced strong etags ([`4abf15f`](https://github.com/chriswk/actix-middleware-etag/commit/4abf15fdd823123c5b2aa5dfe0b23dba36336c82))
 * **[#18](https://github.com/chriswk/actix-middleware-etag/issues/18)**
    - Release v0.4.6 ([`b5a5386`](https://github.com/chriswk/actix-middleware-etag/commit/b5a538684ebc592753aedcbcda8f97768261761d))
</details>

## v0.4.5 (2025-08-04)

### Chore

 - <csr-id-525c98825938244f0161aa837e44433e401f68a0/> release v0.4.5

### New Features

 - <csr-id-41db075859a018eab29396e2d6ed559fcc072994/> add an override for generating strong etags

### Other

 - <csr-id-0ba0f962224d1dc1d74d1841c3b9c962450242c5/> bump actix-service from 2.0.2 to 2.0.3
   Bumps [actix-service](https://github.com/actix/actix-net) from 2.0.2 to 2.0.3.
   - [Release notes](https://github.com/actix/actix-net/releases)
   - [Commits](https://github.com/actix/actix-net/compare/rt-v2.0.2...service-v2.0.3)
   
   ---
   updated-dependencies:
   - dependency-name: actix-service
     dependency-type: direct:production
     update-type: version-update:semver-patch
   ...
 - <csr-id-5ace96fdb432dfc47ae339558937d79301e50697/> bump tokio from 1.43.0 to 1.44.2
   Bumps [tokio](https://github.com/tokio-rs/tokio) from 1.43.0 to 1.44.2.
   - [Release notes](https://github.com/tokio-rs/tokio/releases)
   - [Commits](https://github.com/tokio-rs/tokio/compare/tokio-1.43.0...tokio-1.44.2)
   
   ---
   updated-dependencies:
   - dependency-name: tokio
     dependency-version: 1.44.2
     dependency-type: indirect
   ...
 - <csr-id-f98ff21d547696bac73fd4b983412d7b347c75dc/> bump actions/create-github-app-token from 1 to 2
   Bumps [actions/create-github-app-token](https://github.com/actions/create-github-app-token) from 1 to 2.
   - [Release notes](https://github.com/actions/create-github-app-token/releases)
   - [Commits](https://github.com/actions/create-github-app-token/compare/v1...v2)
   
   ---
   updated-dependencies:
   - dependency-name: actions/create-github-app-token
     dependency-version: '2'
     dependency-type: direct:production
     update-type: version-update:semver-major
   ...
 - <csr-id-9dd7c12c95f03a0302af84d120622279b770b6c8/> bump actix-web from 4.9.0 to 4.11.0
   Bumps [actix-web](https://github.com/actix/actix-web) from 4.9.0 to 4.11.0.
   - [Release notes](https://github.com/actix/actix-web/releases)
   - [Changelog](https://github.com/actix/actix-web/blob/master/CHANGES.md)
   - [Commits](https://github.com/actix/actix-web/compare/web-v4.9.0...web-v4.11.0)
   
   ---
   updated-dependencies:
   - dependency-name: actix-web
     dependency-version: 4.11.0
     dependency-type: direct:production
     update-type: version-update:semver-minor
   ...

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 6 commits contributed to the release.
 - 164 days passed between releases.
 - 6 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 6 unique issues were worked on: [#11](https://github.com/chriswk/actix-middleware-etag/issues/11), [#12](https://github.com/chriswk/actix-middleware-etag/issues/12), [#13](https://github.com/chriswk/actix-middleware-etag/issues/13), [#14](https://github.com/chriswk/actix-middleware-etag/issues/14), [#15](https://github.com/chriswk/actix-middleware-etag/issues/15), [#9](https://github.com/chriswk/actix-middleware-etag/issues/9)

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **[#11](https://github.com/chriswk/actix-middleware-etag/issues/11)**
    - Bump actions/create-github-app-token from 1 to 2 ([`f98ff21`](https://github.com/chriswk/actix-middleware-etag/commit/f98ff21d547696bac73fd4b983412d7b347c75dc))
 * **[#12](https://github.com/chriswk/actix-middleware-etag/issues/12)**
    - Bump tokio from 1.43.0 to 1.44.2 ([`5ace96f`](https://github.com/chriswk/actix-middleware-etag/commit/5ace96fdb432dfc47ae339558937d79301e50697))
 * **[#13](https://github.com/chriswk/actix-middleware-etag/issues/13)**
    - Bump actix-web from 4.9.0 to 4.11.0 ([`9dd7c12`](https://github.com/chriswk/actix-middleware-etag/commit/9dd7c12c95f03a0302af84d120622279b770b6c8))
 * **[#14](https://github.com/chriswk/actix-middleware-etag/issues/14)**
    - Add an override for generating strong etags ([`41db075`](https://github.com/chriswk/actix-middleware-etag/commit/41db075859a018eab29396e2d6ed559fcc072994))
 * **[#15](https://github.com/chriswk/actix-middleware-etag/issues/15)**
    - Release v0.4.5 ([`525c988`](https://github.com/chriswk/actix-middleware-etag/commit/525c98825938244f0161aa837e44433e401f68a0))
 * **[#9](https://github.com/chriswk/actix-middleware-etag/issues/9)**
    - Bump actix-service from 2.0.2 to 2.0.3 ([`0ba0f96`](https://github.com/chriswk/actix-middleware-etag/commit/0ba0f962224d1dc1d74d1841c3b9c962450242c5))
</details>

## v0.4.4 (2025-02-20)

### Chore

 - <csr-id-92dab1b38894e18c6d3c508520227e880869b5a1/> release v0.4.4

### New Features

 - <csr-id-1843d37463add95b0d74f96caa7f27f2b7415f4d/> delta etag is strong not weak

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 2 commits contributed to the release.
 - 2 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 2 unique issues were worked on: [#7](https://github.com/chriswk/actix-middleware-etag/issues/7), [#8](https://github.com/chriswk/actix-middleware-etag/issues/8)

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **[#7](https://github.com/chriswk/actix-middleware-etag/issues/7)**
    - Delta etag is strong not weak ([`1843d37`](https://github.com/chriswk/actix-middleware-etag/commit/1843d37463add95b0d74f96caa7f27f2b7415f4d))
 * **[#8](https://github.com/chriswk/actix-middleware-etag/issues/8)**
    - Release v0.4.4 ([`92dab1b`](https://github.com/chriswk/actix-middleware-etag/commit/92dab1b38894e18c6d3c508520227e880869b5a1))
</details>

## v0.4.3 (2025-02-19)

### Chore

 - <csr-id-e6e9d8d4804bb2e8d4e77818ab301b630d3ed697/> release v0.4.3

### New Features

 - <csr-id-ae9bd61c7ade19971ae1eeed24f153bd732cbd3b/> respect custom etag

### Bug Fixes

 - <csr-id-c1a1e15d68d7fe56698344467f7e80aabd29f9af/> updated secret name

### Other

 - <csr-id-8facf4bad1fda8911acc224af4236517b1f4b790/> move to release-plz for release workflow
   * task: Moves workflow to release-please and setup mergify and dependabot for dependency updates
   
   * chore: bump dependencies
   
   * Just use normal github token when building

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 4 commits contributed to the release.
 - 4 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 3 unique issues were worked on: [#4](https://github.com/chriswk/actix-middleware-etag/issues/4), [#5](https://github.com/chriswk/actix-middleware-etag/issues/5), [#6](https://github.com/chriswk/actix-middleware-etag/issues/6)

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **[#4](https://github.com/chriswk/actix-middleware-etag/issues/4)**
    - Move to release-plz for release workflow ([`8facf4b`](https://github.com/chriswk/actix-middleware-etag/commit/8facf4bad1fda8911acc224af4236517b1f4b790))
 * **[#5](https://github.com/chriswk/actix-middleware-etag/issues/5)**
    - Release v0.4.3 ([`e6e9d8d`](https://github.com/chriswk/actix-middleware-etag/commit/e6e9d8d4804bb2e8d4e77818ab301b630d3ed697))
 * **[#6](https://github.com/chriswk/actix-middleware-etag/issues/6)**
    - Respect custom etag ([`ae9bd61`](https://github.com/chriswk/actix-middleware-etag/commit/ae9bd61c7ade19971ae1eeed24f153bd732cbd3b))
 * **Uncategorized**
    - Updated secret name ([`c1a1e15`](https://github.com/chriswk/actix-middleware-etag/commit/c1a1e15d68d7fe56698344467f7e80aabd29f9af))
</details>

## v0.4.2 (2024-09-03)

<csr-id-6c73e2e23aa0120fd775b112cf664451fd40f21b/>

### Chore

 - <csr-id-6c73e2e23aa0120fd775b112cf664451fd40f21b/> Bump to actix 4.9.0

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 2 commits contributed to the release.
 - 53 days passed between releases.
 - 1 commit was understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Release actix-middleware-etag v0.4.2 ([`842b90f`](https://github.com/chriswk/actix-middleware-etag/commit/842b90f7808a2b0afe3c9476ce9f09d2772f9d76))
    - Bump to actix 4.9.0 ([`6c73e2e`](https://github.com/chriswk/actix-middleware-etag/commit/6c73e2e23aa0120fd775b112cf664451fd40f21b))
</details>

## v0.4.1 (2024-07-11)

### Bug Fixes

 - <csr-id-3fb91b7a78413cd2e3565ce33549cd628f97cd9f/> Added license file

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 3 commits contributed to the release.
 - 1 commit was understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Release actix-middleware-etag v0.4.1 ([`3720ea7`](https://github.com/chriswk/actix-middleware-etag/commit/3720ea7765521642e704b3c591ac6ab72d9e8c77))
    - Release actix-middleware-etag v0.4.0 ([`ca77b11`](https://github.com/chriswk/actix-middleware-etag/commit/ca77b11088997da08990b27605ca7b92378a3fdf))
    - Added license file ([`3fb91b7`](https://github.com/chriswk/actix-middleware-etag/commit/3fb91b7a78413cd2e3565ce33549cd628f97cd9f))
</details>

## v0.4.0 (2024-07-11)

<csr-id-f1ffaad020060379377ed6bdf05eeaab5a5d0a15/>

### Other

 - <csr-id-f1ffaad020060379377ed6bdf05eeaab5a5d0a15/> Bumped dependencies to 4.8 of actix

### Bug Fixes

 - <csr-id-3fb91b7a78413cd2e3565ce33549cd628f97cd9f/> Added license file

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 2 commits contributed to the release.
 - 1 commit was understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Release actix-middleware-etag v0.4.0 ([`194bf91`](https://github.com/chriswk/actix-middleware-etag/commit/194bf919ce052fae8260cfe8c7b088e75c941eec))
    - Bumped dependencies to 4.8 of actix ([`f1ffaad`](https://github.com/chriswk/actix-middleware-etag/commit/f1ffaad020060379377ed6bdf05eeaab5a5d0a15))
</details>

## v0.3.0 (2023-11-23)

<csr-id-864504de94e17b5c1f48e86ffa6ffda3f3703012/>
<csr-id-706fc83a66682004709d164ed10b3ad0407a34c3/>

### Chore

 - <csr-id-864504de94e17b5c1f48e86ffa6ffda3f3703012/> Ready for release
 - <csr-id-706fc83a66682004709d164ed10b3ad0407a34c3/> remove unused import

### Bug Fixes

 - <csr-id-c93f9768d71bdd4a967cc02f68eec816833d607b/> use None body instead of empty

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 4 commits contributed to the release.
 - 295 days passed between releases.
 - 3 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 1 unique issue was worked on: [#2](https://github.com/chriswk/actix-middleware-etag/issues/2)

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **[#2](https://github.com/chriswk/actix-middleware-etag/issues/2)**
    - Use None body instead of empty ([`c93f976`](https://github.com/chriswk/actix-middleware-etag/commit/c93f9768d71bdd4a967cc02f68eec816833d607b))
 * **Uncategorized**
    - Release actix-middleware-etag v0.3.0 ([`f42be50`](https://github.com/chriswk/actix-middleware-etag/commit/f42be50440883bb0620955f2a2f25dffd09c124c))
    - Ready for release ([`864504d`](https://github.com/chriswk/actix-middleware-etag/commit/864504de94e17b5c1f48e86ffa6ffda3f3703012))
    - Remove unused import ([`706fc83`](https://github.com/chriswk/actix-middleware-etag/commit/706fc83a66682004709d164ed10b3ad0407a34c3))
</details>

## v0.2.0 (2023-02-01)

<csr-id-ace591e23b0ee4b31054090bd15aa2782d1e2cbf/>

### Chore

 - <csr-id-ace591e23b0ee4b31054090bd15aa2782d1e2cbf/> Added changelog

### New Features

 - <csr-id-fe10145fa730d9c45deb7e05c594ad5760b9761a/> now includes content length in etag

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 4 commits contributed to the release.
 - 2 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Release actix-middleware-etag v0.2.0 ([`ad14cc8`](https://github.com/chriswk/actix-middleware-etag/commit/ad14cc81231fb5a846d71b2a256b927bef8c6467))
    - Added changelog ([`ace591e`](https://github.com/chriswk/actix-middleware-etag/commit/ace591e23b0ee4b31054090bd15aa2782d1e2cbf))
    - Release actix-middleware-etag v0.2.0 ([`7dc14e6`](https://github.com/chriswk/actix-middleware-etag/commit/7dc14e68c542dba9b83588707afa4780aadd5c71))
    - Now includes content length in etag ([`fe10145`](https://github.com/chriswk/actix-middleware-etag/commit/fe10145fa730d9c45deb7e05c594ad5760b9761a))
</details>

## v0.1.1 (2022-09-29)

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 13 commits contributed to the release over the course of 11 calendar days.
 - 0 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Added publish workflow ([`bd5cd24`](https://github.com/chriswk/actix-middleware-etag/commit/bd5cd246475d89a92fbaac2dd2899931eadd568b))
    - Tighten dependencies ([`f9bd997`](https://github.com/chriswk/actix-middleware-etag/commit/f9bd99743929d6c6ff7d48ecf9a30fb18a11ce98))
    - Updated with rust email address ([`c1c3209`](https://github.com/chriswk/actix-middleware-etag/commit/c1c32097d927772ab7fc66caa2d8aec868eba622))
    - Added cargo tags ([`6f93359`](https://github.com/chriswk/actix-middleware-etag/commit/6f93359e059e0441dbe8322005bd9ca5d37ddac5))
    - Update documentation to actually talk about our middleware ([`cea74b1`](https://github.com/chriswk/actix-middleware-etag/commit/cea74b1e3fa67eb7230640889a1833f1d67ce609))
    - Mention expressjs middleware ([`8e94a50`](https://github.com/chriswk/actix-middleware-etag/commit/8e94a504857b82fac40d744b6c562a38ac8c4405))
    - Updated with docs and only run on GETs ([`212d4b1`](https://github.com/chriswk/actix-middleware-etag/commit/212d4b1493f1a8885749a96209beae29e3bd8295))
    - Fight the borrow checker and the borrow checker wins ([`e29b3ba`](https://github.com/chriswk/actix-middleware-etag/commit/e29b3baa261eadb397a8b817e67312161ddd17bb))
    - Workflow for rust-cache is v2 ([`2790556`](https://github.com/chriswk/actix-middleware-etag/commit/2790556d3eb98a4f0873575b852f33d98ec18e84))
    - Try to setup ci ([`03f259f`](https://github.com/chriswk/actix-middleware-etag/commit/03f259f270ffe483f8f37255a120c007f23f0c33))
    - Added Header trait ([`0fe4a66`](https://github.com/chriswk/actix-middleware-etag/commit/0fe4a6656a1e8586d1b835a39a9fd92ef7e6320f))
    - Added tests and a favicon to test hashing binary files ([`f8501f6`](https://github.com/chriswk/actix-middleware-etag/commit/f8501f6a8be81c04ec897906b272a19f3bf91b21))
    - Initial implementation taken from https://gitlab.com/famedly/company/backend/libraries/actix-etags ([`33f33fe`](https://github.com/chriswk/actix-middleware-etag/commit/33f33fe44f12f3f15981d424d590a1dd12ad4237))
</details>

