# Custom Proffieboard NeoPixel Lightsaber

**AMP Lab — Virginia Tech**

## Project Owner

**Name:** Evan Shelton  
**Virginia Tech Email:** evans06@vt.edu

## Project Overview

The goal of this project is to design, assemble, and program a functional NeoPixel lightsaber powered by a **Proffieboard V3.9** and housed in a Baylan Skoll replica hilt. The project combines mechanical design, electronics integration, and firmware customization.

Planned features include:

- A custom 3D-printed internal chassis for secure, serviceable component mounting.
- A 33-inch, 1-inch-diameter Quantum NeoPixel blade with customizable RGB effects.
- Motion-responsive light and audio effects using ProffieOS.
- A programmable illuminated crystal chamber and emitter accent LEDs.
- A removable protected 18650 rechargeable battery and hilt-button controls.

The final deliverable will be a working lightsaber prototype accompanied by CAD models, wiring documentation, firmware configuration, and test notes.

## What I Hope to Learn

- **Embedded systems:** Configure ProffieOS, customize blade styles and user controls, and connect software behavior to motion sensors, LEDs, and audio.
- **CAD and fabrication:** Model the hilt's usable interior, design a compact chassis and crystal mount, and revise 3D-printed prototypes to meet dimensional constraints.
- **Electronics integration:** Develop a wiring plan, assemble reliable PCB connections, distribute battery power safely, and route wiring through a confined metal enclosure.
- **Verification and troubleshooting:** Test individual subsystems, diagnose hardware/software issues, and document design revisions and results.

## Design and Implementation

This section will be updated as design decisions are finalized and prototypes are built.

### 1. Internal Chassis Design

After receiving and measuring the Baylan Skoll hilt, design a custom CAD chassis to accommodate the Proffieboard V3.9, protected 18650 cell and holder, speaker, switch mechanism, wiring, and illuminated crystal chamber. Print test fits, refine tolerances, and design for electrical insulation and serviceability. Confirm that the selected 28 mm speaker fits before committing to a final mount.

### 2. Electronics Integration

Prepare and verify the electrical layout and assemble the internal electronics, including battery power, Proffieboard, speaker, switch, illuminated emitter connector, and crystal chamber. Check connector polarity, wire sizes, insulation, and battery-contact current handling. Bench-test connections before final mounting. A functional diagram and detailed wiring schematic will be added to the repository as they are developed.

### 3. NeoPixel Blade Assembly

Assemble the **Quantum Battle Blade Builder's Bundle**, including the pixel assembly, diffuser, blade tube, tip, and blade-side connector. Inspect solder joints and test continuity, connector compatibility, LED function, and lighting uniformity before final use. Follow the blade kit's assembly and adhesive instructions.

### 4. Proffieboard Configuration and Programming

Configure the open-source **ProffieOS** firmware for the actual LED counts, control button(s), and hardware connections. Customize the orange-red blade color, ignition and retraction effects, sound fonts, motion responses, and synchronized emitter/crystal lighting. Save original configuration files and document significant changes. Custom C++ firmware modifications are an optional stretch goal.

### 5. Testing and Final Assembly

Verify subsystem function and full-system behavior: power and battery safety, LED operation, speaker sound, motion detection, button behavior, and physical fit. Refine the chassis and wiring as needed, then complete and document the final assembly and demonstration.

## Bill of Materials

Prices reflect the current planning list and may change at checkout. The AliExpress electronics bundle is expected to include the Proffieboard, speaker, switches, wiring, and illuminated hilt-side pogo connector; contents and connector compatibility will be verified on receipt.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Baylan Skoll empty hilt | 1 | $163.10 | [AliExpress](https://www.aliexpress.us/item/3256809025590095.html) |
| Blade plug | 1 | $9.27 | [AliExpress](https://www.aliexpress.us/item/3256808568015431.html) |
| Proffieboard V3.9 electronics bundle | 1 | $36.32 | [AliExpress](https://www.aliexpress.us/item/3256807001225251.html) |
| Quantum Battle Blade Builder's Bundle (33-inch, 1-inch diameter) | 1 | $114.28 | [The Custom Saber Shop](https://www.thecustomsabershop.com/Blades/Pixel-Blade-Supplies/Blade-Builder-Bundles/1-Quantum-Battle-Blade-Builders-Bundle) |
| 3W 28mm Uber Series X speaker | 1 | $8.99 | [The Custom Saber Shop](https://www.thecustomsabershop.com/Electronics/Speakers/28mm-Speakers/3W-28mm-Uber-Series-X-Speaker) |
| Sony 3.7V 15A 3120mAh protected 18650 battery | 1 | $15.00 | [The Custom Saber Shop](https://www.thecustomsabershop.com/Electronics/Batteries-and-Packs/Li-ion-37V/Sony-Li-Ion-18650-37V-15A-3120mAh-PCB-Protected-Rechargeable-Battery) |
| 18650 single-cell holder | 1 | $2.99 | [The Custom Saber Shop](https://www.thecustomsabershop.com/Electronics/Batteries-and-Packs/Holders-/18650-Single-Cell-Holder) |
| Illumicore Crystal | 1 | $14.99 | [The Custom Saber Shop](https://www.thecustomsabershop.com/Electronics/Accent-LEDs/Illumicore-Crystal) |
| Snado universal rechargeable battery charger | 1 | $9.99 | [Amazon](https://www.amazon.com/Intelligent-Snado-Universal-Rechargeable-Batteries/dp/B0721JP6FK) |
| **Estimated component subtotal** | | **$374.93** | |

**Estimated Total Component Cost: $374.93** (excluding shipping, tax, fabrication materials, and additional installation hardware). Verify the battery, holder, charger, speaker, and hilt dimensions before purchasing or assembling them.

## Timeline and Milestones

The schedule depends on component arrival, anticipated near the end of October 2026. Phases may overlap when practical, but the primary build sequence is chassis design, internal electronics integration, blade assembly, and firmware customization.

| Milestone | Target Date | Status |
|---|---|---|
| Project planning and initial bill of materials | October 2026 | Completed |
| Component procurement and inspection | Late October–Early November 2026 | Planned |
| Internal chassis CAD design and prototyping | November 2026 | Not Started |
| Electronics assembly and internal wiring | November–December 2026 | Not Started |
| NeoPixel blade assembly and initial tests | December 2026 | Not Started |
| ProffieOS configuration and customization | January 2027 | Not Started |
| Integration, troubleshooting, and final assembly | January–February 2027 | Not Started |
| Documentation and optional improvements | Spring 2027 | Not Started |

The working target is a functional prototype by **February–March 2027**, with the remainder of Spring 2027 available for refinements and demonstration.

## Progress Log

### 2026-10-16 — Initial Project Planning

**Completed:** Selected the Baylan Skoll hilt, Proffieboard V3.9 electronics bundle, Quantum blade kit, protected battery, speaker, and illuminated crystal; drafted the project proposal, bill of materials, and timeline.

**Next steps:** Finalize orders; verify charger compatibility with the protected 18650, dimensions, and connector compatibility; measure the hilt on arrival; begin chassis CAD design.

Add new dated entries here describing work completed, obstacles, decisions, test results, and next steps.

## Project Files

This repository contains the design files, firmware
configurations, electrical schematics, and images
associated with the lightsaber project.

- [CAD](./CAD/) — Custom chassis models, crystal chamber
  designs, and 3D-printing files.
- [Firmware](./Firmware/) — ProffieOS configuration files
  and custom lighting effects.
- [Schematics](./Schematics/) — Electrical wiring diagrams
  and circuit documentation.
- [Images](./Images/) — Build progress, CAD screenshots,
  and photographs of the completed project.

Files will be added and updated as the project progresses.


## Useful Links

- [ProffieOS source](https://github.com/profezzorn/ProffieOS)
- [ProffieOS documentation](https://pod.hubbe.net/)
- [ProffieOS configuration guide](https://pod.hubbe.net/config/the-config-file.html)
- [The Custom Saber Shop](https://www.thecustomsabershop.com/)

## Project Image

Replace **`hero.png`** in the repository root with a representative project image, keeping the filename unchanged for the AMP Lab website. A photo of the completed build can replace the initial concept image later.
