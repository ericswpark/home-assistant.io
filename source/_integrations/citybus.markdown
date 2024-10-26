---
title: CityBus
description: Instructions on how to use public transit data from CityBus in Home Assistant.
ha_category:
  - Sensor
  - Transport
ha_iot_class: Cloud Polling
ha_release: 2024.11.1
ha_config_flow: true
ha_codeowners:
  - '@ericswpark'
ha_domain: citybus
ha_platforms:
  - sensor
ha_integration_type: integration
---

The `citybus` sensor will give you the next departure time and associated data for the configured CityBus stop. The data comes from [CityBus](https://www.in.gov/citybuslafayette/), the municipal corporation that provides bus services in Tippecanoe County, Indiana.

{% include integrations/config_flow.md %}
