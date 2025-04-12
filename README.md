# Sorel Connect Integration for Home Assistant

Forked from 

A Home Assistant integration for communicating with certain Sorel devices. The device(s) must be connected to Sorel Connect either through a built-in ethernet connection (XHCC) or a separate gateway. See [Sorel Connect](https://www.sorel.de/en/controller/sorel-connect/) or [Sorel Connect HCC](https://www.sorel.de/en/controller/sorel-connect/hcc-sorel-connect/)

This integration lets you read values from devices such as:
* XHCC

## Installation

**Before installing the integration, configure Sorel Connect for the device. See [the instructions here - English PDF](https://www.sorel.de/shared-files/69501/?sorel_connect_en.pdf)**

### Manual

1. Clone the repository to your machine and copy the contents of custom_components/ to your config directory.
1. Restart Home Assistant.
1. Setup integration via the integration page. You will need the same info as for the Sorel Connect page - device id, username, password.

### HACS

1. Add the integration through this link: [![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=david-robson&repository=home-assistant-sorel-connect)
1. Restart Home Assistant.
1. Setup integration via the integration page. You will need the same info as for the Sorel Connect page - device id, username, password.




