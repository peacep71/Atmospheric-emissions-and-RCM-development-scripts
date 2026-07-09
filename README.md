# Emissions and RCM Development Utilities

This repository contains Python utilities developed as part of emissions processing and reduced-complexity model (RCM) development for regional air-quality applications.

The scripts support common preprocessing tasks used in atmospheric modelling workflows, including spatial masking, emissions-sector handling, distance calculations, molecular conversion logic and sector-splitting utilities.

## Purpose

Regional air-quality and reduced-complexity modelling workflows often require several preprocessing steps before model outputs or emissions data can be analysed scientifically. This repository brings together small but reusable scripts that help prepare, transform and organise emissions-related datasets for downstream modelling and diagnostic analysis.

The broader goal is to support reproducible processing of emissions and atmospheric data products used in air-quality scenario analysis, source attribution and policy-relevant modelling.

## What is included

The repository includes utilities for:

- Creating country masks with unique spatial identifiers.
- Building dictionaries and lookup structures for emissions processing.
- Generating or testing emissions fractions for sectoral analysis.
- Applying haversine-based distance calculations.
- Performing molecular or unit-conversion logic in emissions workflows.
- Splitting emissions by sector for air-quality model input or diagnostic analysis.

## Example use cases

These scripts may be useful for workflows involving:

- Regional emissions preprocessing.
- Reduced-complexity air-quality model development.
- Country-level or sector-level emissions attribution.
- Spatial aggregation of emissions data.
- Preparing emissions information for CAMx, WRF-Chem or related air-quality modelling systems.
- Testing how emissions perturbations may affect pollutant concentrations.

## Repository structure

```text
.
├── country_mask*              # Country-mask generation and spatial-ID utilities
├── dictionary*                # Dictionary / lookup-table creation
├── emission_fractions*        # Emissions fraction generation or testing
├── haversine*                 # Distance calculation utilities
├── mol_conversion*            # Molecular / unit-conversion workflow
├── sector_split*              # Sector-splitting utilities
└── README.md
