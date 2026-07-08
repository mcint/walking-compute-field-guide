# Buyer Guide Scaffold

This is a scaffold for a living buyer guide. The goal is to help the next round of actively involved people make reasonable purchases, avoid known-bad integration traps, and report back cleanly.

Do not treat this as an authoritative recommendation list yet. Treat it as a coordination artifact.

## Recommendation levels

Use these labels consistently.

| Label | Meaning |
|---|---|
| `known-good` | Tested as part of a complete rig by at least one participant. Exact topology documented. |
| `candidate` | Plausible and worth testing. Not yet recommended. |
| `baseline` | Useful for comparison, debugging, or establishing a working path. |
| `avoid-for-now` | Known issues, bad fit, unavailable, or wrong integration model. |
| `research` | Interesting but not ready for normal participants. |

## Required fields for hardware entries

Every hardware recommendation or candidate should include:

- Product name and exact model / revision.
- Category.
- Approximate cost.
- Availability: in stock, backordered, used-only, discontinued, regional, unknown.
- Purchase/source links.
- Required integration points.
- Nice-to-haves.
- Known incompatibilities.
- What was actually tested.
- Who tested it and when.
- Open questions.

## Categories

### XR glasses / wearable displays

Required integration points:

- Accepts a display signal from the chosen compute device.
- Works without vendor-only desktop software for basic display use.
- Text is readable enough for terminal/editor/browser use.
- Has a viable prescription or fit-over-glasses path.
- Cable does not make the phone or hub port structurally sad.

Nice-to-haves:

- 3DoF screen anchoring.
- 6DoF or body/world anchoring.
- Dimming or electrochromic shade.
- Low visual fatigue.
- Good indoor social legibility.
- No outward-facing camera, or clear disclosure/status behavior if present.

### Mobile compute

Required integration points:

- Can run the intended OS or stack.
- Can output display over USB-C DisplayPort Alt Mode, HDMI, or another documented path.
- Can pair or connect to the chosen keyboard.
- Can run while powered from a battery or hub.
- Has tolerable thermals under display + keyboard + network use.

Nice-to-haves:

- Mainline-ish Linux support.
- postmarketOS or Mobile NixOS support.
- Replaceable battery.
- Rugged port or repairable daughterboard.
- Suspend/resume that does not ruin the vibe.

### USB-C hubs / adapters

Required integration points:

- Passes display signal to glasses or display.
- Accepts auxiliary power if needed.
- Supports keyboard/input path if it is the central hub.
- Does not require impossible cable orientation or docking ritual.
- Survives sleep/wake and unplug/replug without chaos.

Nice-to-haves:

- Short captive cable or mechanically sane strain relief.
- Clearly labeled ports.
- Works with Android, Linux, Steam Deck, and laptops.
- Does not get hot doing nothing.
- Cheap enough to buy spares.

### Split keyboard / input

Required integration points:

- Usable while standing with arms relaxed.
- Can be mounted, clipped, or suspended near the hips.
- Reliable connection to the compute device.
- Keymap supports text entry and basic pointer/window control.
- Low accidental activation while walking or talking.

Nice-to-haves:

- Open firmware such as QMK/ZMK.
- Low-profile switches.
- Magnetic or quick-release mounting.
- Integrated trackball, trackpad, pointing stick, or pointer layer.
- Easy novice demo mode.

### Batteries, cables, and mounting

Required integration points:

- Battery supports enough USB-C PD wattage for the actual rig.
- Cables are known video-capable when used for display.
- Mounting keeps load off fragile ports.
- Rig survives sitting, standing, stairs, jacket removal, and cable snags.

Nice-to-haves:

- Battery display or telemetry.
- Replaceable cables.
- Color-coded cable roles.
- Printed or labeled strain-relief pieces.
- Public-space-safe cable routing.

### Projectors / socially cast displays

Projectors are a separate display category, not merely an accessory. They may solve a different problem: letting nearby collaborators see what the wearer is seeing.

Required integration points:

- Accepts video from the compute device or hub.
- Bright enough for the intended indoor use.
- Can be worn, clipped, set down, or quickly aimed.
- Has a sane power path.
- Does not create unsafe glare or surprise projection onto people.

Nice-to-haves:

- USB-C video input.
- Battery powered.
- Keystone correction.
- Short-throw behavior.
- Low fan noise.
- Visible status that projection is active.

## Candidate hardware table template

| Category | Product | Status | Cost | Availability | Required integration points | Nice-to-haves | Tested? | Notes |
|---|---|---:|---:|---|---|---|---|---|
| XR glasses | TODO | candidate | TODO | TODO | TODO | TODO | no | TODO |
| Mobile compute | TODO | candidate | TODO | TODO | TODO | TODO | no | TODO |
| USB-C hub | TODO | candidate | TODO | TODO | TODO | TODO | no | TODO |
| Split keyboard | TODO | candidate | TODO | TODO | TODO | TODO | no | TODO |
| Battery/cables/mounting | TODO | candidate | TODO | TODO | TODO | TODO | no | TODO |
| Projector | TODO | candidate | TODO | TODO | TODO | TODO | no | TODO |

## Known-good rig table template

| Rig | Tester | Date | Compute | OS | Display | Hub | Input | Battery | Status | Notes |
|---|---|---|---|---|---|---|---|---|---|---|
| Android baseline | TODO | TODO | TODO | Android | TODO | TODO | TODO | TODO | untested-template | Establish a working display/hub/input baseline before debugging Linux. |

## Failed / weird tests table template

| Date | Tester | Component | Failure mode | Reproducible? | Workaround | Notes |
|---|---|---|---|---|---|---|
| TODO | TODO | USB-C hub | Glasses detected only without auxiliary power | TODO | TODO | TODO |
| TODO | TODO | Cable | Charges but no display | TODO | Replace with video-capable cable | TODO |

## Minimum viable first buyer list

Before recommending purchases to new participants, try to assemble:

1. A known-good baseline rig.
2. A cheaper equivalent candidate.
3. A Linux-first rig attempt.
4. A failure list for hubs/cables.
5. A social-norms cheat sheet.
6. A shared-display/projector option for demos and collaboration.
