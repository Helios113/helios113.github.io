---
title: 'Trip to Japan and SISPAD 2023: SISPAD DAY 3'
description: 'Sispad Day 3: Sensors and Optoelectronics'
slug: sispad-japan-3
date: 2023-09-29 00:00:00+0000
image: IMG_0293.jpeg
categories:
    - Conferences
    - SISPAD
    - SISPAD23
tags:
    - Conferences
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

## Self-Consistent Monte Carlo Device Simulation of Capture-Excitation Processes of Carriers

Sony presented a [Monte Carlo](https://en.wikipedia.org/wiki/Monte_Carlo_method) Device simulator for carriers. Monte Carlo is an interesting simulation method. I need to write a tutorial on how to effectivly implement MC methods in python.  

## Bayesian Optimization of Light Grating for High Performance Single-Photon Avalanche Diodes
Single-Photon Avalanche Diodes (SPADS).
Laser illuminates scene and SPAD captutes the relection. One can compute the distance to an object. Used for autofocus of smartphones. SPADS are time of flight sensors. One can model SPADS as electrical devices or optical devices.

How to find optimal grating and DTI parameters? One can use empirical equations [[Ono 2021]](https://pubmed.ncbi.nlm.nih.gov/34265921/). However, this method uses ray tracing which does not always work based on wavelengths.

If we want to optimize the light absortion, we can express absorbtion as a function of geometry and then use baysian optimisation to find the optimal parameter set.

## Full-Band Monte Carlo Study of Hot Carriers for Advection-Diffusion Monte Carlo Simulations

## Band structure and optical absorption of strained SiGeC alloys: a Tight-Binding approach

## Electrolyte-Gated FET-based Sensing of Immobilized Amphoteric Molecules Including the Variability in Affinity of the Reactive Sites