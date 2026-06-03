---
title: 'Availability Tool'
summary: A tap-to-select web app that turns your free slots into a copy-paste message for WhatsApp, Signal, or any chat.
date: 2025-06-03T00:00:00+01:00
draft: false
link: https://pezmc.github.io/availability-tool/
github: https://github.com/Pezmc/availability-tool
---

A lightweight web app that eliminates the weekly chore of manually composing "when I'm free" messages. Every time someone asks "when are you free?", you end up cross-referencing your calendar, checking what day dates fall on, and formatting everything nicely. This tool reduces that to under 30 seconds.

The interface shows the next 21 days as a vertical list. Each day has three tap targets: morning, afternoon, and evening. Tap once to mark yourself as free (green), again for "if need be" (amber), and a third time to remove. A live preview updates in a sticky footer, and a single Copy button puts the formatted text on your clipboard.

Four output formats are available: a traditional bullet-point list, a compact monospace grid, an emoji-based visual grid, and a natural conversational sentence that reads like you typed it yourself. All formats paste cleanly into WhatsApp, Signal, Telegram, Messenger, SMS, and email.

Entirely client-side with no backend, no accounts, and no tracking. Built with Vue 3, TypeScript, and Vite. Mobile-first with dark mode support.
