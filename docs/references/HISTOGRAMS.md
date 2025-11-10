# Histograms 101 (Image Intensity)

- A histogram shows the distribution of pixel intensities (X = intensity; Y = count).
- **Wide** distributions imply higher contrast; **narrow** imply lower contrast.
- Avoid **clipping** at the minimum (0) or maximum (e.g., 4095 for 12‑bit) to preserve detail.

**Display Min/Max in Micro‑Manager**
- In **Live** view, adjust the histogram sliders to change display range (does not alter underlying pixel values).
- Ensure the curve fits within your min/max to avoid hiding real pixels.
