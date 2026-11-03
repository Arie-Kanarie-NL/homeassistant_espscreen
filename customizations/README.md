# Guition 4-inch lamp styling (experimental)

The firmware source `components/smart_display/runtime_tiles.h` on this test branch has been modified.

Intended changes for ordinary Home Assistant light tiles:
- cyan border: #30DFF2, approximately 3 scaled pixels
- icon centered above the name and state
- larger, centered text when the cell size permits
- retain the existing Tessera background color
- leave non-light tiles unchanged

Base: Tessera screens-v0.4.96 / firmware 0.60.0. The user's current Guition displays run firmware 0.59 and 0.56.

**Not yet compiled or tested on physical hardware. Do not flash this branch to a display yet.**

Before installation: compile for Guition ESP32-S3-4848S040, audit short/tall/wide lamp tile layouts, confirm OTA compatibility and test on one display before updating the second. Do not commit any ESPHome Wi-Fi, OTA or API credentials to GitHub.

GitHub Actions have been enabled for this fork; this documentation update requests a fresh CI run for the draft pull request.
