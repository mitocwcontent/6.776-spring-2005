---
content_type: page
title: Projects
uid: f37aa8c0-8f4e-902f-c366-474bab3f974f
---

Final Project Assignment - RF Power Amplifier Design
----------------------------------------------------

Work in a group of two. Only one report should be turned in per group.

### Project

The objective of this project is to design and simulate a 2 GHz power amplifier for narrowband communication systems. The power amplifier to be designed will output a constant-envelope signal suitable for phase modulation systems. The amplifier must meet the specifications listed below. It is recommended that you first select the overall circuit topology and do enough hand calculations to determine that the required specifications are approximately met. For hand calculations, use the device parameters published in the spec sheets.

Inductors should be first designed according to the reference paper from Thomas Lee's group (Mohan, et. al. "Simple, Accurate Expressions for Planar Spiral Inductances." _JSSC_ (Oct 1999): 1419-1424.) The inductor (or transformer) geometry should then be entered in ASITIC and its model extracted.

Spectre RF should be used to simulate and fine-tune the amplifier performance - be sure to include the full inductor models (i.e., including loss and parasitic capacitance) in your schematic.

| SpecificationS | ValueS |
| --- | --- |
| Power Supply | Single < 1.8 V |
| Load | 50Ω (resistive) |
| RF Output Power (at 50Ω load) | 100mW+-10% |
| Center Frequency | 2.0 GHz |
| Power Efficiency | \> 75% |
| RF Input Power | < 20mW |
| Distortion | < -30dBc |
| Inductor Q (@2GHz) | Use ASITIC |
| Capacitor Q (@2GHz) | Infinite |
| Process | TSMC 0.18µ no high voltage transistor option 

  

At no time allow the voltage across the gate oxide of any transistor to exceed 2.5V, even during transients.

The write-up for this project **is limited to 3 pages** plus schematics, Spectre plots, inductor design, layout, and any other figures. The report is due in session 25. This is not a trivial design, so start working soon.