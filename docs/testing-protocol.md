# Testing Protocol

The testing protocol exists to prevent USB-C and wearable-compute mythology from entering the guide as fact.

A component is not known-good because it worked once in someone's hand. A component is known-good when the exact topology is documented and reproducible.

## Layers

Test in layers.

1. Bench test.
2. Power test.
3. Wear test.
4. Social test.
5. Field report.

## Bench test

Record exact models for every part.

- Compute device.
- OS and version.
- Display or glasses.
- Hub or adapter.
- Battery / charger.
- Cable model, length, and whether it is known video-capable.
- Keyboard/input device.

Steps:

1. Confirm compute device can drive a normal external display.
2. Confirm glasses/display work from a known-good laptop or handheld.
3. Confirm the exact cable carries video.
4. Confirm hub passes video with no auxiliary power.
5. Confirm hub passes video with auxiliary power.
6. Confirm keyboard/input works.
7. Confirm sleep/wake behavior.
8. Confirm unplug/replug behavior.
9. Record display resolution and refresh rate.
10. Record heat and power behavior after 30 minutes.

## Power test

Record:

- Starting battery percentage for compute device and battery pack.
- Whether the compute device charges, holds level, or drains.
- Runtime under realistic use.
- Whether display brightness changes power draw meaningfully.
- Whether the hub gets hot.
- Whether the battery pack renegotiates or drops power when load changes.

## Wear test

Steps:

1. Wear the rig standing for 15 minutes.
2. Walk around the space.
3. Sit down and stand up three times.
4. Climb stairs if relevant.
5. Type for 10 minutes.
6. Use pointer/window controls.
7. Have a normal conversation while wearing it.
8. Remove and reattach the rig.
9. Check whether any port, cable, or mount is under strain.

Record:

- Comfort.
- Visual fatigue.
- Heat.
- Cable snags.
- Mount failures.
- Whether the rig changes posture or gait.
- Whether it looks weirder than expected. Be honest. We are not trying to LARP around reality.

## Social test

Ask at least one nearby person:

- Could you tell whether I was available to talk?
- Did the hardware look like it might be recording?
- Was the display socially distracting?
- Was there a clear way for me to signal attention?
- Would this be fine in a workshop? A meeting? A casual conversation? A public hallway?

Record:

- Context.
- Whether people were already aware of the project.
- Any concern about gaze, recording, or attention.
- Any useful status convention.

## Result labels

| Result | Meaning |
|---|---|
| `passes-baseline` | Works for the stated topology and basic use. |
| `partial` | Useful but missing a key integration requirement. |
| `failed` | Does not work for the tested topology. |
| `inconclusive` | Test setup was incomplete or ambiguous. |
| `do-not-buy-for-this` | Failure is strong enough that participants should avoid it for this project. |

## Field report template

```markdown
# Field report: <rig or component>

- Tester:
- Date:
- Location:
- Status: passes-baseline / partial / failed / inconclusive / do-not-buy-for-this

## Components

- Compute:
- OS:
- Display/glasses/projector:
- Hub/adapter:
- Keyboard/input:
- Battery/charger:
- Cables:
- Mounting:

## What I expected

## What happened

## Exact topology

Describe what plugs into what.

## Tests run

- [ ] Bench test
- [ ] Power test
- [ ] Wear test
- [ ] Social test

## Results

## Cost / availability

## Required integration points met

## Missing / failed integration points

## Nice-to-haves observed

## Recommendation

## Photos / diagrams

## Open questions
```
