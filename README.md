# Dragon Curve Fractal – COMP3710 Demo 1 (Task 3)

This repository contains my implementation of the **Dragon Curve fractal** using Python and Matplotlib for COMP3710.

The dragon curve is generated using an **L-system** with rules:
- `F → F+G`  
- `G → F–G`

It demonstrates **self-similarity** and has a fractal dimension ≈ 2, meaning it is *almost space-filling*.

---

#Features
- L-system implementation (`dragon_curve_sequence` and `draw_dragon_curve`)
- Multiple visualisations:
  - Default blue line
  - Coloured progression using `viridis` colormap
  - Red version
  - Dashed green line

---

#AI PROMPT LOG 

Prompt 1:
"Help me write the Python code to generate and plot a dragon curve fractal using an L-system."

AI Output (excerpt): Provided basic sequence function (F → F+G, G → F–G) and a turtle-style drawing function.

What I learned:

-The dragon curve is created by rewriting rules (L-system).

-Each “+” and “–” corresponds to a 90° turn, which generates the folding pattern.

Prompt 2:
"Why is my dragon curve showing up as only a flat line?"

AI Output (excerpt): Explained that I needed to update the angle when encountering “+” and “–”, and to use plt.axis("equal") to avoid distortion.

What I learned:

Importance of updating the angle correctly when turning.

Using equal axis scaling so the curve is not squashed into a line.

