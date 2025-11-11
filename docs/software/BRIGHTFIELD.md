# Brightfield Imaging Workflow

1. Insert an objective; in Micro‑Manager, select the matching **Objective** (update each time you change objectives to keep metadata correct).
2. Set filter layer to **Empty** (pull slider to the position labeled *Empty*).
3. Place the slide (coverslip **down**). Enable **Auto Shutter**.
4. Choose camera: **Kikker** (monochrome; default) or **Rana** (color for histology, etc.).
5. Set **mirror slider**: **left** for color (Rana), **right** for mono (Kikker).
6. Channel → **Mid RGB**; click **Live** to open Preview and Histogram windows.
7. Adjust exposure to spread the histogram without clipping (typ. **1–50 ms**). If the histogram is left‑skewed (dark), increase exposure; if right‑skewed (overexposed), decrease.
8. Focus with **X/Y** micrometers and **Z** focus. Avoid contacting the slide.
9. Confirm dynamic range: in 12‑bit mono, avoid pixels at **4095** (saturation). Adjust exposure or LED intensity accordingly.
10. Save: click **Save** in the Preview window, or **Stop Live → Snap → Save**.
