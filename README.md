# Spiral
its awesome

Three-body worlds â one self-contained HTML file each. **Open `index.html`** for the viewer: `â¹ PREV / NEXT âº`, arrow keys, `CYCLE` auto-advance (20s), `â` opens the current world standalone. Deep-link any world with the URL hash (`#03`).

| # | World | Source |
|---|-------|--------|
| 01 | Anchored Springs | original |
| 02 | Relationship Space | original |
| 03 | Figure Eight | Moore 1993 Â· Chenciner & Montgomery 2000 |
| 04 | Moth I | Å uvakov & DmitraÅ¡inoviÄ 2013 (I.B.1) |
| 05 | BrouckeâHÃ©non | Broucke 1975 Â· HÃ©non 1976 |
| 06 | Lagrange Triangle | Lagrange 1772 â unstable for equal masses; the instability is the demo |
| 07 | Newest | later catalogue addition (van derbei suite) |
| 08 | Yin-Yang I | Å uvakov & DmitraÅ¡inoviÄ 2013 (II.C) |

**Receipts.** The catalogued worlds use published initial conditions; each file's header comment carries its source, convention, period, and a numerical verification note (the state returns to its start within one period under the page's own integrator). 04 and 08 are close-encounter families â the honest cost of a fixed-step integrator is a slow precession, noted in their headers. Every world is disturbable: click/tap to push the nearest body, or hit DISTURB; RESET restores the catalogued orbit.

**Adding a world:** drop in `09.html`, add one row to the `WORLDS` list in `index.html`. That's the whole mechanism.
