# Contributing

This repo is for coordination around walking / walkable compute rigs.

The highest-value contributions are:

1. Exact field reports.
2. Failed integration reports.
3. Candidate hardware with cost, availability, and explicit integration requirements.
4. Buyer-guide updates backed by tests or clearly marked as candidates.
5. Social-norms notes from actual interactions.

## Preferred workflow

- Open an issue for hardware recommendations, field reports, or integration problems.
- Use PRs for docs, structured data, and MediaWiki-ready updates.
- Include exact model numbers.
- Include prices and availability when known.
- Say what was actually tested.
- Mark untested claims as untested.

## Recommendation labels

| Label | Meaning |
|---|---|
| `known-good` | Tested as part of a complete rig by at least one participant. Exact topology documented. |
| `candidate` | Plausible and worth testing. Not yet recommended. |
| `baseline` | Useful for comparison, debugging, or establishing a working path. |
| `avoid-for-now` | Known issues, bad fit, unavailable, or wrong integration model. |
| `research` | Interesting but not ready for normal participants. |

## Required hardware-report details

Include:

- Product name and exact model / revision.
- Category.
- Approximate cost.
- Availability.
- Purchase/source links.
- Required integration points.
- Nice-to-haves.
- Known incompatibilities.
- What was actually tested.
- Who tested it and when.
- Open questions.

## Social norms

When reporting social interaction, include whether people were already opted into or aware of the project. The boundary between "cool wearable display" and "why are you wearing a possible camera in my face" is not abstract. Record it cleanly.

## MediaWiki

Keep `mediawiki/Walkable_Compute.mediawiki` pasteable into Noisebridge MediaWiki. If a PR changes public-facing content, update the MediaWiki version or note that it needs manual sync.
