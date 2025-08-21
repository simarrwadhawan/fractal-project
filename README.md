# Dragon Curve Fractal – COMP3710 Lab 1 (Part 3)

This repository contains my implementation of the **Dragon Curve fractal** using Python and Matplotlib for COMP3710.

The dragon curve is generated using an **L-system** with rules:
- `F → F+G`  
- `G → F–G`

It demonstrates **self-similarity** and has a fractal dimension ≈ 2, meaning it is *almost space-filling*.

---

## 📊 Features
- L-system implementation (`dragon_curve_sequence` and `draw_dragon_curve`)
- Multiple visualisations:
  - Default blue line
  - Coloured progression using `viridis` colormap
  - Dashed red line
- Substantial analysis:
  - Estimated **fractal dimension** using the **box-counting method**
  - Dimension ≈ 2 → nearly space-filling, consistent with theory
