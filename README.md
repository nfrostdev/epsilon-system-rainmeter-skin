# Epsilon System Rainmeter Skin

## How do I get this skin centered on my screen?
1. Open RainMeter
2. Go to the "Settings" Tab
3. Click the "Edit settings" button.
4. Find the `[epsilon-system-rainmeter-skin]` block.
5. Remove any `WindowX` or `WindowY` attributes.
6. Paste the following under the block:
```ini
WindowX=50%@1
WindowY=50%@1
AnchorX=50%@1
AnchorY=50%@1
```
**Replace the "1" with the monitor number you want the skin to be centered on.**