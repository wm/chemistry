# Chemistry study guide

A single-page, interactive study guide on ions, electron transfer, and static
electricity, written at a 10th-grade chemistry level. It explains the ideas
behind the unit's questions without answering them.

**Live site:** <https://wm.github.io/chemistry/>

## Contents

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
