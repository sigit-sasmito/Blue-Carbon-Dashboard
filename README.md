# Blue Carbon Dashboard

This repository contains Google Earth Engine (GEE) code to **visualise and quantify mangrove-based blue carbon outcomes**, including:

- Mangrove loss (annual and cumulative)
- Mangrove loss drivers (e.g., aquaculture, degraded land, other conversion pathways)
- Carbon emissions associated with mangrove loss and conversion
- Mangrove restoration potential (low/medium/high suitability)
- Climate change mitigation potential (avoided emissions + carbon removals)

## Overview

The analysis is primarily based on **spatial overlays of published and pre-processed datasets**, including mangrove baseline extent, annual forest cover loss/deforestation layers, mapped loss drivers, and restoration opportunity layers. Data sources and key assumptions are documented within the code comments and asset descriptions.

## Platform

All scripts are developed to run in the **Google Earth Engine** Code Editor and can be adapted for deployment as a **GEE App** (interactive dashboard).

## Notes for reproducibility

- The scripts reference specific GEE assets (Image / FeatureCollection paths). Users must have access to these assets or replace them with equivalent public datasets.
- Default spatial resolution and chart aggregation scales are defined in the configuration section of the script.
- Results depend on the chosen emission factors and restoration removal rates documented in the code.
