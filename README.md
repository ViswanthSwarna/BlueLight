# 11 LED MCPCB

KiCad project for an aluminum-core LED board:

- Board size: 50 mm x 50 mm square
- Mounting: 4x M3 non-plated holes, 40 mm x 40 mm pattern
- LED layout: 11 LEDs in 3 rows, arranged 3 / 4 / 4
- Electrical layout: one series string from `VIN+` to `VIN-`
- LED pad geometry follows the supplied drawing: two 0.55 mm x 1.35 mm SMD pads with a 0.25 mm gap

Manufacturing notes:

- Order as aluminum PCB / MCPCB, single-sided copper.
- Confirm the LED package and current before fabrication. The footprint matches the provided solder-pad drawing, but LED polarity and package height should be checked against the exact LED datasheet.
- Use thermal paste or a thermal pad between the MCPCB and heat sink.
- The 50 mm square / 40 mm mounting pattern is intentionally conservative so it can be mounted to common small LED or electronics heat sinks.
