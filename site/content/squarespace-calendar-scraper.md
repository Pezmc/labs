---
title: 'Squarespace Calendar Scraper'
summary: Scrapes availability from Squarespace Scheduling Calendars
date: 2025-01-08T00:00:00+01:00
draft: false
link: ''
github: https://github.com/Pezmc/squarespace-calendar-availability-scraper
---

A tool that uses GitHub Actions to scrape availability of appointments managed with Squarespace Scheduling (also known as Acuity Online Appointment Scheduling) and send push notifications through PushOver when new appointment slots become available.

Created after frustration booking appointments with my therapist. She would be booked months in advance and cancellations would pop up, but there was no way to know about them other than checking the calendar daily. The script runs automatically via GitHub Actions, monitors the calendar for new availability, and sends instant notifications when appointment windows open up.