---
title: 'Leuven Appointment Checker'
summary: Monitors the City of Leuven appointment system for earlier openings
date: 2026-01-08T00:00:00+01:00
draft: false
link: ''
github: ''
---

A Python automation that monitors the City of Leuven's Qmatic-based appointment booking system for earlier available slots. Runs hourly via GitHub Actions behind a Belgian VPN tunnel (the site geo-blocks non-Belgian traffic), sends mobile push notifications via Pushover when earlier appointments appear, and can automatically rebook to the earliest available time.

Built out of frustration with the city's appointment system, where popular services like residence registration are booked weeks in advance and cancellations appear without notice.
