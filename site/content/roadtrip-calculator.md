---
title: 'Road Trip Calculator'
summary: Genetic algorithm-based optimizer planning road trips
date: 2020-08-14T00:00:00+01:00
draft: false
link: ''
github: https://github.com/Pezmc/roadtrip-calculator
---

A genetic algorithm-based optimizer for finding the shortest driving route between multiple waypoints. The solver uses a genetic algorithm to find an optimal route visiting all waypoints.

It loads waypoints from a KML file (which can be created using Google My Maps, Google Earth, or other tools), queries the Google Maps API for driving distances and durations between waypoints, then evolves routes over many generations to minimize total travel time. The result is an interactive HTML map showing the best route found.

The tool caches distance lookups to avoid repeated API calls and can be configured with different population sizes and generation counts to balance between solution quality and computation time.

Adapted from Randy Olson's Shortest Route Program, modified by Andrew Liesinger.

