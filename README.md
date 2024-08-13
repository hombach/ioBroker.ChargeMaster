![Logo](admin/chargemaster.png)
# ioBroker.chargemaster

[![NPM version](https://img.shields.io/npm/v/iobroker.chargemaster?style=flat-square)](https://www.npmjs.com/package/iobroker.chargemaster)
[![Downloads](https://img.shields.io/npm/dm/iobroker.chargemaster?label=npm%20downloads&style=flat-square)](https://www.npmjs.com/package/iobroker.chargemaster)
![node-lts](https://img.shields.io/node/v-lts/iobroker.chargemaster?style=flat-square)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/iobroker.chargemaster?label=npm%20dependencies&style=flat-square)

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/hombach/iobroker.chargemaster/test-and-release.yml?branch=main&logo=github&style=flat-square)
[![CodeQL](https://github.com/hombach/ioBroker.chargemaster/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/hombach/ioBroker.chargemaster/actions/workflows/codeql-analysis.yml)
[![Appveyor-CI](https://ci.appveyor.com/api/projects/status/github/hombach/ioBroker.chargemaster?branch=master&svg=true)](https://ci.appveyor.com/project/hombach/iobroker-chargemaster)
[![SNYK Known Vulnerabilities](https://snyk.io/test/github/hombach/ioBroker.chargemaster/badge.svg)](https://snyk.io/test/github/hombach/ioBroker.chargemaster)

## Versions

![Beta](https://img.shields.io/npm/v/iobroker.chargemaster.svg?color=red&label=beta)
![Stable](https://iobroker.live/badges/chargemaster-stable.svg)
![Installed](https://iobroker.live/badges/chargemaster-installed.svg)

[![NPM](https://nodei.co/npm/iobroker.chargemaster.png?downloads=true)](https://nodei.co/npm/iobroker.chargemaster/)

## Adapter to manage one or multiple EV-chargers with use of PV-energy
**!!! THIS ADAPTER IS STILL REPRESENTING AN DEVELOPMENT STATE !!!**

Adapter to manage one or multiple EV-chargers (wallboxes) with use of PV-energy. Adapter currently handles with up to 3 EV wallboxes to manage charging available grid power  with potential use of PV surplus energy. 

## Settings
To connect to the wallboxes type in the states with needed data in the config.

## Notes
This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers. For more details and for informations on how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

## Changelog
! Note that missing version entries are typically dependency updates for security.

### 0.9.2 (14.08.2024)

* (HombachC) fixed vulnerability in dependency

### 0.9.1 (06.08.2024)

* (HombachC) fixed issues detected by repository checker (#494)
* (HombachC) code cleanups

### 0.9.0 (20.04.2024)

* (HombachC) BREAKING: dropped support for node.js 16 (#455)
* (HombachC) BREAKING: js-controller >= 5 is required (#456)

### 0.8.5 (27.03.2024)

* (HombachC) updated CI definitions, switched to node 20 as main test scenario
* (HombachC) corrected io-package.json according to new schema
* (HombachC) bumped dependencies

### 0.8.4 (29.12.2023)

* (HombachC) BREAKING: dropped support for js-controller 3.x
* (HombachC) Year 2024 changes
* (HombachC) Bump axios to 1.6.3 because of vulnerability

### 0.8.3 (29.10.2023)

* (HombachC) Bumb adapter core to 3.x
* (HombachC) Bump axios to 1.6.0 because of vulnerability

### 0.8.2 (01.10.2023)

* (HombachC) Several dependency updates
* (HombachC) Fixed acknowledging of state changes (#339)

### 0.8.1 (29.08.2023)

* (HombachC) bumped dependencies, added min/max to settings state defaults

### 0.8.0 (23.06.2023)

* (HombachC) changed config screen to admin 5 solution

### 0.7.2 (19.06.2023)

* (HombachC) Removed Travis 

### 0.7.1 (13.06.2023)

* (HombachC) Fixed typo in docu, added translations 

### 0.7.0 (11.06.2023)

* (HombachC) BREAKING: dropped node.js 14 support
* (HombachC) Add tests for node.js 20, removed for node.js 14, bumped dependencies
* (HombachC) BREAKING: dropped ioBroker.admin 4 support

### 0.6.3 (29.12.2022)

* (HombachC) bumped dependencies and year 2023 changes

### 0.6.2 (11.09.2022)

* (HombachC) fixed error in calc with active charge current

### 0.6.1 (08.09.2022)

* (HombachC) bump @iobroker/testing from 3.0.2 to 4.1.0

### 0.6.0 (09.08.2022)

* (HombachC) fix error in max total current, fix error in charge manager

### 0.5.1 (06.06.2022)

* (HombachC) removed gulp, bumped dependencies, small code tweaks

### 0.5.0 (09.05.2022)

* (HombachC) BREAKING: dropped node.js 12 support
* (HombachC) Add tests for node.js 18, removed for node.js 12
* (HombachC) bumped dependencies to non node.js 12 support

### 0.4.4 (27.04.2022)

* (HombachC) fixed vulnerability, bumped dependencies

### 0.4.3 (22.02.2022)

* (HombachC) added github tests for MAC-OS and Windows

### 0.4.2 (21.02.2022)

* (HombachC) changed statemachine to async; bumped dependencies

### 0.4.1 (18.02.2022)

* (HombachC) fixed error in charger communication; added ci test

### 0.4.0 (14.02.2022)

* (HombachC) introduced automatic adaption to the amount of configured chargers; bugfixes for cleaner run without config

### 0.3.2 (14.02.2022)

* (HombachC) fixing test automation, several bugfixes for cleaner run without config

### 0.3.1 (29.01.2022)

* (HombachC) added sentry statistics; optimized logging; fixed type conversion bug

### 0.3.0 (28.01.2022)

* (HombachC) first public release for iOBroker latest repo; added sentry support

### 0.2.0 (18.12.2021)

* (HombachC) dropped node.js 10 support; bumped dependencies

### 0.1.5 (15.10.2021)

* (HombachC) fixed vulnerability; improved docu

### 0.1.2 (02.05.2021)

* (HombachC) code cleanup and optimization, fixed onStateChange

### 0.1.1 (30.04.2021)

* (HombachC) fixed errors with js-controller 3.3.x, bumped dependencies

### 0.1.0 (11.04.2021)

* (HombachC) first running version, fixed to 3 boxes

### 0.0.7 (31.03.2021)

* (HombachC) added MaxAmpTotal, MinAmpWallBox, MaxAmpWallBox

### 0.0.6 (23.03.2021)

* (HombachC) added collection and calc of total charge power

### 0.0.4 (15.03.2021)

* (HombachC) fix error in foreign state popup

### 0.0.2 (06.01.2021)

* (HombachC) fix errors to get it running in old single wallbox mode

### 0.0.1 (01.01.2021)

* (HombachC) initial release

## Tested with
- 3x go-E Charger & Kostal PikoBA

## License
MIT License

Copyright (c) 2021-2024 Christian Hombach

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
