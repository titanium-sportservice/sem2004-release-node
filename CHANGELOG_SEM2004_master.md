# Changelog

This document maintains a list of released versions and changes introduced by them.
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)

## [9.3.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v9.2.0...v9.3.0) (2025-06-21)


### Features

* Club edit option in Entry Form ([61e70a2](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/61e70a23b7ae60080c10a6d8303db3be9227bee8))

## [9.2.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v9.1.0...v9.2.0) (2025-06-21)


### Features

* export sport class status to WPS record file ([e516106](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/e5161068e5775dfd8051ac25bfeafc3f5ee41da6))


### Bug-Fixes

* day time clock format and DotNetLib-fix ([62187f0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/62187f0fb9b884b53f4def67a45d8aaeecdbe94e))
* Record Check time format ([27e499e](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/27e499eb9859f18c52ab0bc5593487414d5ba24f))
* Time Format in DotNetLib ([177f3fb](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/177f3fb5c81b4d709566ed87b52aaa2caa77822c))
* update DotNetLib - point calculation ([16eda86](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/16eda86bf7c012fbc40c366c3d55bafd3a9f430f))

## [9.1.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v9.0.0...v9.1.0) (2025-05-29)


### Features

* feature update of DotNetLib ([427f5ef](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/427f5ef8af1d07dd6ecb1e8a583bc83345471249))

## [9.0.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v8.1.0...v9.0.0) (2025-05-26)


### ⚠ BREAKING CHANGES

* Database migration of table "start", "ergebnis"

The database field "rekordLong" and "rekordIdLong" was added to the
"Wettkampf" table.
The database field "rankIndex", "medal" and "teamPoints" was added to
the"ergebnis" table.

### Features

* Net8 CurrentHeatForm and SwimPointLib implemented ([b8e49f2](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/b8e49f27aa3ddcdfe514f68fdf8ca317ce470798))
* RecordLib and FQQL Manager implemented in DotNetLib ([79fe210](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/79fe210bf0252d01125004c753b6a43e3fed67de))

## [8.1.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v8.0.0...v8.1.0) (2025-05-12)


### Features

* input of RAW times in the entry list by using "*" ([4ce6355](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/4ce63559a70ac7e9b7592ecbb9fcea602fd7ddd9))

## [8.0.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v7.10.0...v8.0.0) (2025-04-11)


### ⚠ BREAKING CHANGES

* Database migration of table "Wettkampf"

The database field "addResultsFromEventId" was added to the
"Wettkampf" table.

### Features

* now you can combine the results from different events ([40f3bd5](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/40f3bd5ac7dd733748ddd70edbf1e4a6c6a00ca6))
* **ui:** show eventId in event tree ([b167200](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/b167200afb85ef5b7337f2baeee05f88876a54ba))


### Bug-Fixes

* **build:** registering of DotNetInterop ([18546d2](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/18546d29504bbd4ef76df4223cceaf369f3a6c1b))
* **build:** update Register od DLLs ([640af89](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/640af895a94cf96bc5a1103a68490e121b13b9ca))
* **install:** store Path and Version in registry key ([b3f0cc5](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/b3f0cc5ca5d343f7e73cd4a994bc4659fe1dc09e))

## [7.10.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v7.8.0...v7.10.0) (2025-04-10)


### Features

* **build:** syncro auf development and master pipeline ([1fd82d0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/1fd82d0774ae1a41b10eae78373314d85bd03598))
* **install:** add DotNetInterop to installer ([f2efb81](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/f2efb817f6435b952669d57e04b978ed6f3fc2dd))

## [7.8.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v7.7.0...v7.8.0) (2025-04-10)


### Features

* **build:**  update master pipeline for perfect build ([bcd0ebb](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/bcd0ebb1aad43ce13f4eaef1797c8094a488297f))

## [7.7.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v7.5.0...v7.7.0) (2025-04-09)


### Features

* add Instaler Project ([04063ba](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/04063baab12aa4186d1b25d930e6f7e13193a1b7))
* create meeting from menu ([97ca25d](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/97ca25d0d6348878aa7311083c052f8f1d7633d5))

## [7.5.0](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/compare/v7.4.0...v7.5.0) (2025-04-07)


### Features

* WPS 2025 points implemented ([1580c4d](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/1580c4dca08d1d632fc8930098a62c5a677466e0)), closes [#440](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/issues/440)


### Bug-Fixes

* **build:** remove Athenticate from master pipeline ([487275d](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/487275d6b8c72a47ed3e7f67e043e1fade11245b))
* **build:** tag-force for master pipeline ([b81d164](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/b81d1642fb12143a1c3d9085647d1e848ef6ab6d))
* nuget push now by command for dev ([25dcd67](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/25dcd67a2e58af3116c268cf9b02bd20dacce042))
* nuget push now by command for master ([e1724c1](https://dev.azure.com/titanium-sportservice/SPORT_SWM_SEM2004/_git/SPORT_SWM_SEM2004/commit/e1724c1f373a588f805a4863e2cebd827e2d75fd))
