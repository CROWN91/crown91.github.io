BLACK CROWN CLEAN UI

- Removed black rectangle overlays and baked progress image.
- Firmware text is a live DOM element from PS4 browser user agent.
- Cache percentage is shown on cache installer pages only, based on AppCache progress events.
- No firmware number is fabricated for desktop browsers.
- Original exploit scripts and payloads were not changed.
- Real PS4 and offline operation must be tested on hardware.


## GoldHEN activity indicator (2026-11-24)
On g2all/index.html, an indeterminate red activity bar is shown during exploit execution on PS4 when AppCache is present. It disappears on explicit success/error text signals. No fabricated completion percentage or performance claims. Existing exploit payloads unchanged. AppCache manifest version comments bumped. Note: other success notifications not written to #msgs cannot be reliably detected by this indicator.
