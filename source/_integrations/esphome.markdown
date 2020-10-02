---
title: ESPHome
description: Support for ESPHome devices using the native ESPHome API.
featured: true
ha_category:
  - DIY
ha_release: 0.85
ha_iot_class: Local Push
ha_config_flow: true
ha_codeowners:
  - '@OttoWinter'
ha_domain: esphome
---

This integration allows you to connect [ESPHome](https://esphome.io) devices directly to Home Assistant with the [native ESPHome API](https://esphome.io/components/api.html).

## Automatic Configuration

An ESPHome node can be set up via the **Integrations** menu: **Configuration** > **Integrations**:

* Click the orange `+` on the lower-right of the screen and select **ESPHome**

* Complete the dialog box and click `SUBMIT`. 
    * **Host**: If the node is called `livingroom` in ESPHome, the Hostname would be `livingroom.local`
    * **Port**: The default port is `6053`

**Note:** If the node has a password set, Home Assistant prompt for it. 

Upon completion, all entities for that specific ESPHome node will be accessible through Home Assitant.
