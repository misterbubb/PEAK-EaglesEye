# Eagle's Eye

Ever squint at something in the distance and think, _“Man, I wish I could zoom in with my face”?_ Now you can.  
**Eagle's Eye** adds a configurable zoom feature with scroll support, a binocular overlay (optional).

## Installation

Drop the `EaglesEye.dll` into your game's BepInEx `plugins` folder:  
`<game directory>\BepInEx\plugins`

## Usage

- **Hold** your configured key (default: `C`) to zoom in.
- **Scroll** while zoomed in to fine-tune your view.
- Release the key to return to your original FOV like nothing happened.
- Optional binocular overlay.

## Configuration

A config file is generated at:  
`<game directory>\BepInEx\config\mrbub.peak.eagleseye.cfg`

Available settings:

- **ZoomKey**  
  Key used to zoom in.  
  _Default: `C`_

- **ZoomFovMin**  
  Minimum zoom FOV when fully zoomed in.  
  _Default: `1`_

- **ZoomFovMax**  
  Maximum FOV when zooming out.  
  _Default: `60`_

- **ShowBinocularOverlay**  
  Whether to show the binocular overlay when zoomed in.  
  _Default: `false`_

## Known Side Effects

- May lead to judging your teammates from a distance.
- May provoke the urge to narrate in a nature documentary voice.

## Credits

Made with love by **mrbub**.  
Inspired by the need to see stuff better.
