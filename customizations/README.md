# Guition 4-inch lamp styling (draft)

This is a **test patch**, not a flashed or compiled firmware release.

Intended changes to ordinary Home Assistant light tiles only:
- cyan border: #30DFF2, approximately 3 scaled pixels
- icon centered above the name and state
- larger, centered text when the cell size permits
- retain the existing Tessera background color
- leave non-light tiles unchanged

Base source: Tessera screens-v0.4.96 / firmware 0.60.0. The user's current panels run firmware 0.59 and 0.56.

The patch is in `customizations/guition-lamp-styling.patch`. It has **not been applied** to `components/smart_display/runtime_tiles.h` on this branch. Do not use this branch to update a screen yet.

Before installation: apply the patch to the source, compile for Guition ESP32-S3-4848S040, verify short/tall/wide light tile layouts, confirm OTA compatibility, and test on one display first. No user Wi-Fi, OTA, or API credentials are included.
