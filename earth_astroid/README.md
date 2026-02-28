### Key Improvements Explained

1. **Crater scaling**: uses a slightly improved exponent (0.29) and distinguishes between continental and oceanic targets.
2. **Size‑resolved dust**: fine dust (optical) and coarse dust (ballistic) with different fallout rates, giving more realistic τ evolution.
3. **Greenhouse forcing**: CO₂ and methane now contribute to warming, modulating the temperature after dust clears.
4. **Ocean carbonate chemistry**: simple box model for DIC and pH, allowing pH to recover slowly via carbonate compensation (implicitly through DIC adjustment).
5. **Silicate weathering**: draws down CO₂ over millennia, preventing permanent high CO₂.
6. **Biodiversity recovery**: now possible if environmental conditions (temperature, pH) improve.
7. **Omori‑law aftershocks**: seismic intensity decays as 1/(1+Kt), more realistic than exponential.
8. **Ejecta pulse**: heating scaled by re‑entering mass, and methane release tied to ocean boiling.
9. **Variable time stepping**: small steps early to resolve rapid changes, larger steps later for efficiency.
10. **Methane lifetime**: depends on UV (via dust optical depth) to reflect shielding.

These changes directly address the major shortcomings identified in the analysis: the too‑small crater, constant CO₂, fixed pH, non‑recovering biodiversity, and simplistic seismicity. The model is still a research tool, but now incorporates much more Earth system science.
