# Tradeverse Market Context Seed

Seed feed for Tradeverse market context data used by trading indicators.

## Purpose
This repository publishes lightweight machine-readable context data for trading tools.

## Current v1 news feed
- `news/BOB_EVENT_SLOT_1.txt`
- `news/BOB_EVENT_SLOT_2.txt`

Each slot contains either:
- `NONE`
- or `YYYY-MM-DD|HH:MM|ALIAS|IMPACT`

## Intended flow
1. Internal source of truth is maintained outside this repository.
2. Export scripts generate current seed slot values.
3. Pine indicators read the slot files through `request.seed()`.

## Directories
- `news/` current exported seed slots
- `schemas/` lightweight data structure references
- `scripts/` helper / export scripts
