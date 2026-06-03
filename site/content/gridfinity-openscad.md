---
title: 'Gridfinity Selective Bases'
summary: OpenSCAD contribution to skip inner bases on gridfinity bins
date: 2025-05-25T00:00:00+01:00
draft: false
link: https://github.com/kennetek/gridfinity-rebuilt-openscad/pull/303
github: https://github.com/Pezmc/gridfinity-rebuilt-openscad
---

A contribution to the [gridfinity-rebuilt-openscad](https://github.com/kennetek/gridfinity-rebuilt-openscad) project adding a `base_locations` option that lets users skip rendering bases in the center of a grid bin, keeping only corners or edges. This reduces print time and saves plastic for larger bins.

Inspired by a Reddit thread about omitting inner base squares. Two modes are offered: corners only and edges only. Without supports, bridging ability limits how large you can go with corners-only (3x3 worked fine on a Prusa MK3, but larger sizes needed supports).
