[![GitHub Release][releases-shield]][releases]
[![License][license-shield]][license]

[![hacs][hacsbadge]][hacs]
[![Project Maintenance][maintenance-shield]][user_profile]

_Component to integrate with [MagiQtouch heating/cooling controllers][ha_magiqtouch]._

**This component will set up the following platforms.**

Platform | Description
-- | --
`climate` | Heating / Cooling control.

Note: Ensure that you have created an account using the Seeley Magiqtouch app and registered it with your system.

## Installation

1. Open HACS
1. Open Custom repositories (Menu at top right)
1. In the Custom repositories dialogue go to the Repository field and enter "https://github.com/andrewleech/ha_magiqtouch" and under category choose Integration" click "ADD"
1. Click "+ Explore and download repositories" and search for "magiqtouch", click to open then click download. It will download to custom_components/magiqtouch
1. Once it is downloaded you will need to reboot.

## Configuration is done in the UI
1. Go to settings, Devices & Services
1. "+ Add Integration" and search for "Seeley MagIQtouch" and select the matching integation.
1. Enter the Email / User account details for the Seeley Magiqtouch, and click submit. 

This will add your MagIQtouch system as a entity - climate.(system/zone name)
<!---->

***

[ha_magiqtouch]: https://gitlab.com/alelec/ha_magiqtouch
[hacs]: https://hacs.xyz
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[license]: https://github.com/custom-components/ha_magiqtouch/blob/main/LICENSE
[license-shield]: https://img.shields.io/github/license/custom-components/ha_magiqtouch.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Andrew%20Leech%20%40alelec-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/custom-components/ha_magiqtouch.svg?style=for-the-badge
[releases]: https://github.com/custom-components/ha_magiqtouch/releases
[user_profile]: https://github.com/andrewleech
