# Hakushin Ring

A desk armillary: a fixed hoop on a stand, three nested rings that each turn on
their own axis, and a fox crest spinning at the centre. 182 mm wide, 226 mm
tall, about 360 g.

The whole design lives in `hakushin-ring.json`: its parameters (start with
`outer_or`, which scales everything), parts, assembly, connections and twelve
requirements. `hakushin-ring.step` is the same assembly as solid geometry, for
a slicer or any CAD tool.

## How it moves

| Part | Turns on | Axis |
| --- | --- | --- |
| Hoop | fixed in the saddle | none |
| Outer ring | 2 pins pressed into the hoop | vertical |
| Inner ring | 2 pins pressed into the outer ring | horizontal |
| Innermost ring | 2 pins pressed into the inner ring | in the inner ring's plane |
| Fox crest | brass axle pressed into the innermost ring | across the innermost ring |

Each ring clears the next by 3 mm, and a 3 mm nylon spacer on every pin keeps
the rings concentric.

## What to make

| Qty | Part | How |
| --- | --- | --- |
| 1 | Hoop, 182 OD x 6 | Print flat, white PETG |
| 1 | Outer ring, 160 OD x 12 | Print flat, white PETG |
| 1 | Inner ring, 118 OD x 6 | Print flat, white PETG |
| 1 | Innermost ring, 96 OD x 6 | Print flat, white PETG |
| 1 | Stem and saddle | Print upright, white PETG, 4 walls |
| 1 | Fox crest, 6 thick | Print flat, silk gold PLA |
| 4 | Outer clasp | Print on its side, silk gold PLA |
| 2 | Inner clasp | Print on its side, silk gold PLA |
| 1 | Crown emblem, 2 thick | Print flat, silk gold PLA |
| 1 | Base, 130 dia x 14 | Turn or CNC from walnut, or print |
| 1 | Crest axle | 2 mm brass rod, cut to 96 mm |
| 2 | Crest spacer | 4 mm brass tube, 2.3 mm bore, cut to 18.3 mm |

The hoop is the largest print and needs a 220 mm bed. 0.2 mm layers and 4
walls are enough for every part; none needs supports.

## What to buy

| Qty | Item |
| --- | --- |
| 2 | Dowel pin 3 x 20, hardened steel (ISO 8734) |
| 2 | Dowel pin 3 x 26 |
| 2 | Dowel pin 3 x 16 |
| 6 | M3 nylon spacer, 3 mm long, about 5.5 mm OD |
| 2 | M3 x 20 pan head screw and M3 nut |
| 1 | M4 x 16 socket head screw |
| 1 | M4 x 8 heat-set insert |
| 2 | Silk tassel, about 60 mm, with cord |
| | Cyanoacrylate glue |

## After printing

- Ream the pin holes that grip a pin to 2.95 mm so the pin presses in: both
  holes in the hoop, the side holes of the outer ring, and the top and bottom
  holes of the inner ring.
- Drill the holes a ring turns on to 3.3 mm: top and bottom of the outer ring,
  the sides of the inner ring, top and bottom of the innermost ring.
- Drill the crest's cross hole through at 2.4 mm, and the innermost ring's two
  side holes at 1.95 mm for the axle.
- Sand each nylon spacer to 2.8 mm.

## Assembly, from the centre outward

1. Push the axle through one side of the innermost ring, thread on a spacer
   tube, the crest and the second tube, then press the axle into the far side.
2. Hold the innermost ring inside the inner ring with a spacer in the gap at
   top and bottom, and press a 3 x 16 pin in through each of the inner ring's
   top and bottom holes until it is flush. Glue an inner clasp over each pin head.
3. Hold the inner ring inside the outer ring with a spacer either side, and
   press a 3 x 26 pin in through each side of the outer ring until flush. Glue
   an outer clasp over each pin head, the two upper clasps at 60 degrees either
   side of the top, and the crown emblem on the front face between them.
4. Hold the outer ring inside the hoop with a spacer at top and bottom, and
   press a 3 x 20 pin in through the top and bottom of the hoop until flush.
5. Melt the insert into the bottom of the stem. Screw the stem to the base
   from below with the M4 screw.
6. Seat the hoop in the saddle slot, bottom pin down, so the saddle floor holds
   that pin in. Clamp it with the two M3 screws and nuts.
7. Tie a tassel through each eye in the hoop.

## Checks the model makes

At the dimensions in this repository all twelve are met and no two parts intersect: every ring and the
crest turn a full revolution without touching the next, the pins engage at
least 4 mm, the outer ring clears the saddle and the tassels, the hoop fits a
220 mm bed, and the base is wide enough not to tip.

The model checks geometry, not strength or print tolerances: test-fit one pin
hole on your own printer before printing the rings.
