# Chemistry study guide

A single-page, interactive study guide for 10th-grade chemistry. Like the
[algebra guide](https://wm.github.io/algebra-two/), each topic is split into a
**Checklist**, **Patterns** (the cue that tells you which method applies),
**Solved problems** from class worksheets, and a **Practice test** with new
numbers.

**Live site:** <https://wm.github.io/chemistry/>

## Topics

- **Static electricity** — the original interactive guide (details below).
- **Subatomic particles & fields** — built from *Quiz 2 Review: Subatomic
  Particles and Electric Fields*: labeling an atom, charging by rubbing,
  drawing electric / gravitational / magnetic fields, forces on a test
  particle, and particle tables (mass = p + n, charge = p − e).
- **Isotopes & atomic mass** — built from *Isotopic Abundance practice
  problems*: weighted averages, missing isotope mass, and missing abundances
  (x and 100 − x).

### Notes on the worksheets

- The isotope sheet's intro names carbon's second isotope as carbon-14 (14.003,
  0.55%). Carbon's second stable isotope is carbon-13 (13.003, ~1.1%); the
  sheet's arithmetic still gives 12.011, so the method is unaffected.
- Isotope #5 depends on how many digits of bromine's atomic mass you use:
  79.904 gives 80.918 amu; 79.90 gives 80.909 amu.

## Static electricity contents

- **Lithium atom builder** — add or remove an electron to see Li, Li⁺, and Li⁻.
  Proton and neutron counts stay fixed; only the net charge changes.
- **Reading an ion's symbol** — what the superscript says about electrons vs
  protons, and why lithium forms Li⁺ far more readily than Li⁻.
- **What can move, and what can't** — why electrons transfer between objects
  while protons stay in the nucleus; conservation of charge.
- **The rules of attraction** — two charges with sign toggles and a distance
  slider: like charges repel, opposites attract, closer is stronger.
- **Electron transfer: balloon and hair** — a step-by-step rubbing simulation
  showing electrons moving from hair to balloon and the resulting attraction.
- **Polarization** — why a charged balloon sticks to a neutral wall.
- **Same atom, different models** — shell, electron cloud, plus-and-minus, and
  macroscopic views, each with what it shows and what it leaves out.
- **Two scales, one event** — macroscopic observations paired with their
  atomic-scale causes.
- **Key words** and **Check yourself** — vocabulary plus six practice questions
  with hidden answers. These were written for the guide and are not from the
  teacher.

## Structure

`index.html` is self-contained — no build step, no dependencies to install.
Styles and scripts are inline; the diagrams are inline SVG that follows the
light/dark theme. Google Fonts is the one external resource, loaded at view
time, with system-font fallbacks.
