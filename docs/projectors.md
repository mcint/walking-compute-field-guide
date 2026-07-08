# Projectors and Socially Cast Displays

Projectors are a first-class display path for walking compute.

XR glasses make compute private and gaze-obscuring. A projector can sometimes invert that: the wearer can socially cast a screen, letting nearby collaborators see what is being referenced.

This is not necessarily for full productivity. It may be best for demos, pairing, teaching, debugging, and making attention visible.

## Why projectors matter

Potential benefits:

- Makes the hidden display socially visible.
- Helps collaborators understand what the wearer is seeing.
- Supports ad-hoc pairing without a desk.
- Can turn a wall, table, floor, or board into a shared screen.
- May reduce awkward “are you looking at me or a screen?” ambiguity.

Potential problems:

- Low brightness.
- Short battery life.
- Fan noise.
- Keystone/focus fiddliness.
- Privacy leaks.
- Projecting onto people or unwanted surfaces.
- Awkward cable and mounting topology.

## Projector categories

| Category | Use case | Risks |
|---|---|---|
| Pocket projector | Set down or hand-aimed demos | Power, brightness, focus. |
| Wearable chest/shoulder projector | Social casting while standing | Glare, aim, body movement. |
| Clip-on short-throw projector | Wall/table demos | Mounting complexity. |
| Phone-as-projector-adjacent display | Not literal projection; external shared screen | Smaller social surface, but simpler. |

## Required integration points

A projector candidate should document:

- Input path: USB-C video, HDMI, wireless casting, or other.
- Whether it works from Linux / Android / Steam Deck / laptop baseline.
- Power input and battery life.
- Mounting options.
- Brightness in the intended space.
- Fan noise.
- Focus and keystone behavior.
- Whether it can be safely aimed without blinding or annoying people.
- Whether it encourages oversharing private screen contents.

## Nice-to-haves

- USB-C DisplayPort Alt Mode input.
- Battery powered.
- Works while charging.
- Quiet enough for conversation.
- Short-throw or tabletop-friendly optics.
- Physical shutter or obvious off state.
- Quick blank-screen control.
- A mounting point that is not cursed.

## Test protocol

1. Connect from a known-good laptop.
2. Connect from the walking compute rig.
3. Test with and without auxiliary power.
4. Project terminal/editor/browser text.
5. Check readability at 1m, 2m, and 3m.
6. Try wall, table, floor, and whiteboard surfaces.
7. Try a five-minute conversation while it is on.
8. Ask nearby people whether it is helpful, distracting, or creepy.
9. Record battery drain and heat.
10. Record whether it makes the rig more socially legible.

## Open questions

- Is projector casting mostly a demo mode or a daily mode?
- Does a projector reduce gaze ambiguity enough to justify complexity?
- What brightness is enough for Noisebridge lighting?
- Is body-mounted projection too unstable while walking?
- Can a tiny projector be paired with XR glasses as a “show what I see” mode?
