jQuery UI labeledSlider
=======================

*Work in Progress*

This plugin wraps the functionality provided by the jQuery UI Slider plugin, an adds two main features:

- Ticks, little lines that indicate where the slider will snap to.
- Labels, instead of passing in numbers, and steps and so forth, you pass in an array, and then you are able to access these labels the same way you are able to get the value of the slider. Good for non-numeric selections and ranges.

Drawbacks
---------

Currently some things are hardcoded, we are working to remove these restrictions.

- The `slide` event is set for you and not-overridable.
- `range` mode is always enabled.
- `step` is enabled, so the slider snaps to locations, not free moving.
