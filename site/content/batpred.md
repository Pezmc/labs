---
title: 'Batpred Contributions'
summary: Solar surplus EV charging and extended scheduling for Home Assistant
date: 2026-06-01T00:00:00+01:00
draft: false
link: https://github.com/springfall2008/batpred
github: ''
---

Contributions to [Predbat](https://github.com/springfall2008/batpred), an open-source Home Assistant add-on for home battery prediction and charging automation supporting many inverter types.

**Solar Surplus Car Charging** ([PR #3791](https://github.com/springfall2008/batpred/pull/3791)): Adds automatic diversion of excess solar generation to EV charging instead of exporting to the grid at low feed-in rates. Includes hysteresis to prevent flapping from clouds, respects force-export windows and battery-discharge protection, and publishes sensors for use in HA automations.

**Extended Car Charge Scheduling** ([PR #3891](https://github.com/springfall2008/batpred/pull/3891)): Allows the car charging ready-by deadline to extend beyond 24 hours (e.g. for weekends or holidays), with a date dropdown showing days up to the forecast horizon.
