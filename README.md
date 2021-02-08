# Epsilon System Rainmeter Skin
This is a work in progress and not yet finished.

## Requirements
* [CoreTemp](https://www.alcpu.com/CoreTemp/) must be running.
* [SpeedFan](http://www.almico.com/speedfan.php) must be running.

SpeedFan and unfortunately gives inaccurate readings for some CPU temperatures, if not all, otherwise it would be the only requirement.

## Installation with Git
1. Navigate to your RainMeter Skins folder in a terminal. (Usually C:\Users\YOUR_USERNAME\Documents\Rainmeter\Skins)
2. `git clone https://github.com/nfrostdev/epsilon-system-rainmeter-skin.git` 
3. (Optional if not being changed.) Install GT America Mono, located in the `font` folder of this skin.

## Installation via File Download
1. [Download the skin.](https://github.com/nfrostdev/epsilon-system-rainmeter-skin/archive/main.zip)
2. Extract the content to your RainMeter `Skins` folder. (Usually C:\Users\YOUR_USERNAME\Documents\Rainmeter\Skins)
3. (Optional if not being changed.) Install GT America Mono, located in the `font` folder of this skin.

## Usage
1. Open RainMeter and if you don't see the skin click "Refresh all".
2. Open `epsilon-system-rainmeter-skin` and load `EpsilonSystem.ini`.

## Customization
If you'd like to tweak some settings, most things are declared in variables at the top of the skin file.

### Safe Variables to Change
The following variable values are safe to change:
* `UserFontFace` name of font installed on your system
* `TextColor` rgba value
* `ShadowColor` rgba value

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
*Replace the "1" with the monitor number you want the skin to be centered on.*