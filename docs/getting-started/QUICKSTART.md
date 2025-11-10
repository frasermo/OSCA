# Quickstart (5–10 minutes)

1. Place **OF01 openFrame** on a stable, low‑vibration surface (≥110×80 cm). Do **not** move after assembly.
2. Mount **OF02 Stage & Transillumination**: align arrows →1/→2; tighten **S02/S03** with **T03 (2.5 mm hex)**.
3. Attach **OF03 Transillumination**: USB toward pillar; seat onto posts; tighten the two top screws (**T03**).
4. Install cameras: **OF09 Kikker (mono)** and **OF11 Rana (color)** with labels up; hand‑tighten (don’t over‑tighten).
5. Fit **OF04 IRIS‑400**: add **OF06 ring adaptor** (three grub screws **T02**), insert **OF07** tube to the guideline, support body on **OF08 pedestal** ~20 cm left of IRIS port.
6. Cable up:
   - **IRIS**: **OF22** controller OUTPUT ⇄ **OF04** via **OF19**; power via **OF23** (arrows up).
   - **Cameras**: **OF16 USB + OF20 12V** → Kikker; **OF15 USB** → Rana.
   - **Hub**: **OF17** → Laptop (P01).
   - **Transillumination**: **OF18 USB‑C** → Laptop (P02).
7. Remove **transport screws** on multiband cube and mirror slider; store safely.
8. Power laptop; login **IDM / OSCA2025**. Launch **Micro‑Manager**, choose **Default User**, config: `CellCam MultimodeLED.cfg`.
9. **Brightfield**: filter to **Empty**, Channel → **Mid RGB**, **Live**, exposure **1–50 ms** typical.
10. **Fluorescence**: filter to **Multiband**, camera **Kikker**, IRIS **R/G/B/UV** LED, **Live**, exposure **100–800 ms** typical.
