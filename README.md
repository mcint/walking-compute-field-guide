# Walking Compute Field Guide

Field notes, buyer-guide scaffolding, and coordination docs for a Noisebridge walking / walkable compute group.

The project is starting as a practical buyer's guide, but the actual goal is broader: build a shared record of rigs, hardware candidates, failed adapters, integration constraints, social norms, and field reports.

This repo is deliberately not an affiliate-list style "best XR glasses" page. It is a coordination surface for people actively trying rigs and reporting what works.

## Core rig shape

A typical experimental rig combines:

- XR glasses or another body-worn display, mostly for mundane computing.
- Mobile compute, ideally a phone or pocket device running Linux, postmarketOS, Mobile NixOS, NixOS-derived setups, or another self-sovereign stack.
- A USB-C hub or adapter that can pass display signal, power, and input without weird topology failures.
- Split keyboard halves mounted near the hips, hanging from a belt, attached to clothing, or otherwise reachable while arms hang naturally.
- Battery pack, cables, mounts, strain relief, and weather/social sanity.
- Optional socially visible output, including wearable or pocket projectors that can cast a screen for nearby collaborators.

## What belongs here

- Known-good rigs with exact component chains.
- Candidate hardware and why it might be promising.
- Failed tests, especially USB-C hub failures.
- Cost and availability notes.
- Integration requirements and nice-to-haves.
- PRs or issues from people trying hardware.
- Notes on social interaction, consent, gaze ambiguity, and boundary protocols.

## Main docs

- [Buyer guide scaffold](docs/buyers-guide.md)
- [Testing protocol](docs/testing-protocol.md)
- [Social norms](docs/social-norms.md)
- [Projectors and shared display](docs/projectors.md)
- [Naming notes](docs/naming.md)
- [MediaWiki seed page](mediawiki/Walkable_Compute.mediawiki)

## Structured data

- [`data/components.yaml`](data/components.yaml): candidate and tested hardware.
- [`data/rigs.yaml`](data/rigs.yaml): assembled rig reports.

## Contribution flow

1. Open an issue using one of the templates.
2. Include exact model numbers, links, prices, availability, and integration points.
3. If you tested it, say exactly what was connected to what.
4. If it failed, file it anyway. Failed tests are first-class output.
5. PRs are welcome for docs, component records, rig reports, and MediaWiki-ready summaries.

## Current status

Seed scaffold. No authoritative picks yet. The first useful milestone is three or more complete field reports covering:

- a known-good Android baseline,
- a Linux-phone or pocket-Linux candidate,
- a split-keyboard + wearable-display social/use test.
