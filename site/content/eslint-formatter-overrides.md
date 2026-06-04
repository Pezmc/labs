---
title: 'ESLint Formatter Overrides'
summary: Generates ESLint overrides to disable rules for all existing failures
date: 2026-03-19T00:00:00+01:00
draft: false
link: ''
github: https://github.com/Pezmc/eslint-formatter-overrides
---

An ESLint formatter that generates a set of file-level overrides disabling rules for all existing failures. This lets you adopt new or stricter ESLint rules immediately on new code while grandfathering existing violations, avoiding the need to fix hundreds of existing issues before you can enable a rule.

Run ESLint with this formatter, and it outputs a configuration block you can paste into your ESLint config. New files and new code are held to the stricter standard from day one, and existing violations can be cleaned up incrementally.
