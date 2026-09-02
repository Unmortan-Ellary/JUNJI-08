# // JUNJI-08
<img width="1217" height="946" alt="image" src="https://github.com/user-attachments/assets/0e586b30-309a-4390-9d95-89287c928fc9" />

### Synth's Core Ideas:
- **Analog Modeling:** 8-Voice Polyphonic analog modeling synthesizer based on `KORG Minilogue`. 
- **Chrome as Sound Engine:** Powered by Chrome's builtin `Web Audio API`, `Web MIDI API` etc, works on any `Chromium` based browser.
- **Powerful Sequencers:** Two powerful independent `128-Step` Sequencers with Automation support (any knob), flexible Arpeggiators.
- **Wide Panorama:** Voice stereo spread support with `Delay` and Lush `Reverb` modules.
- **Simplicity:** Easy to understand interface, curated features with "less is more" ideology.
- **Dependency-Free:** Completely offline, No downloads, no Python, no Node.js - just a single compact (100~ kb) HTML file that runs in your browser.
- **Open Source:** under the Apache 2.0 License.

### What's new?
- v0.601 Release.

### Features:

1. **Oscillators:**
    - Two classic oscillators.
    - `Sine`, `Triangle`, `Sawtooth`, `Square` waveforms with Wavefolding control as `Shape`.
    - Second Oscillator supports `Cross-Mod`, `Hard-Sync Mod`, `Ring Mod`.
    - `Octave` and `Coarse` pitch controls.
    - Mixer with `White Noise` and `OSC1` and `OSC2` levels.

2. **Filter:**
    - `2-Pole` or `4-Pole` modes.
    - `20-20k` Cutoff range.
    - Resonance without Self-Oscillation. 
    - Pre-Filter `Drive` based on aggressive Wavefolding.
    - Supports `Velocity TO Cutoff` and `Key-Tracking TO Cutoff` functions.

3. **Envelopes:**
    - `AMP ENV` - Classic volume control ADSR Envelope.
    - `MOD ENV` - Custom ADSR Envelope control for different Targets: `Mod TO Pitch`, `Mod TO Shape`, `Mod TO Cutoff`, `Mod TO Resonance`.

4. **Delay:**
    - Include `High-Pass Filter`, signal can be `PRE-Filtered` or `POST-Filtered`, `20-20k` Cutoff range.
    - Controls `Mix`, `Time`, `Feedback` to form any type of delay behavior.

5. **Reverb:**
    - Designed to imitate wide spaces with dynamic reflections, creating a lush textures.
    - Controls `Mix`, `Time` (controls room size), `Tone` (controls the high-frequency presence).

6. **Patch Library:**
    - Supports 20 Patch Presets.
    - `Left Mouse Click` to Load Patch, `Right Mouse Click` to Save current Patch.
    - `Export` Saves current Patch as `*.patch` file (Hold `ALT` to Export it to Clipboard).
    - `Import` Loads `*.patch` files (Tries to Load it from Clipboard first).

7. **MIDI Support:**
    - Support for `MIDI` Devices via `Web MIDI API`.
    - Support `MIDI` Mapping for any Control Element.
    - `Right Mouse Click` on any Knob, Slider, Switch to Assign Custom `CC` on your Device.

8. **Miscellaneous:**
    - Keyboard velocity support via `Vel TO Amp` Knob.
    - Two `128-Step` Sequencers with Automation.
    - Virtual Keyboard with Octave selection.
    - Wide Stereo Voice `Spread` Function.
    - `Glide` From Note to Note Function.
    - `Transpose` Note Function.

### Sequencers Guide:

1. **Step Recording:** 
    - Use `Left Mouse Click` to Select any `Step` as your Starting Point.
    - Press a `Note` and Release it to Record single `Note`. 
    - Hold `Note` and ADD any amount of `Notes` to Record a Chord.
    - Press `Esc` or `Left Mouse Click` on Glowing `Step` to Cancel `Step Recording`.
    - Hover with a `Mouse Cursor` over `Step` to get its State Info.
    <img width="1550" height="830" alt="brave_screenshot" src="https://github.com/user-attachments/assets/51677ac3-87c4-4220-8d9d-df8420b7d2c4" />

2. **Step Mods:**
    - `Rest`: Use `Right Mouse Click` on Recorded `Step` to Mark it as `Rest` for skipping, you can also press `REST` Button durring `Step Recording`.
    - `Hold`: Use `ALT + Right Mouse Click` on Recorded `Step` to Mark it as `Hold`: If Next `Step` have Same `Note` this `Note` will be Hold.
    - `Repeat`: Use `SHIFT + Left Mouse Click` on Recorded `Step` to Mark it for `Repeat \ Ratchet`: Dots will Appear on Top of `Step` representing Repeats to make (2-4 Times).
    - `Gate`: Use `ALT + Left Mouse Click` on Recorded `Step` to Mark it for `Gate`: Dots will Appear on Bottom of `Step` representing Gate of Release (25-50-75%).
    <img width="1546" height="824" alt="brave_screenshot" src="https://github.com/user-attachments/assets/0010915f-a0a3-43e3-8d2d-72b9d790f5c7" />

3. **Copy / Delete:**
    - `Delete`: Use `CTRL + Right Mouse Click` on Recorded `Step` to Mark it as `Starting Point`, then Select `Step` as `Ending Point`: All `Steps` in this `Starting-Ending` Range will be `Deleted`, can be Same Single `Step`.
    - `Copy`: Use `CTRL + Left Mouse Click` on Recorded `Step` to Mark it as `Starting Point`, then Select `Step` as `Ending Point`, finally Select `Step` to `Paste` All `Steps` in Copied `Starting-Ending` Range, can be Same Single `Step`.
    <img width="1554" height="832" alt="brave_screenshot" src="https://github.com/user-attachments/assets/2ff35bf8-aa26-405f-8b71-81a419d85991" />

4. **Automation Mods:**
    - Use `Left Mouse Click` to Select any `Step` as your Starting Point.
    - While `Step Recording` is active Tweak any number of Knobs / Sliders / Switches / Buttons and Press `Enter`.
    - Corresponding `Automation Mods` will be created inside Selected `Step`, only final Tweaks are Saved.
    - On `Play` this `Automation Mods` will be applied for single active `Step`, temporary overriding current settings.
    - To `Delete` Saved `Automation Mods` Select Target `Step` and Press `Enter`, then Press `Enter` again.
    - Hover with a `Mouse Cursor` over `Step` to get its State Info.
    <img width="1550" height="830" alt="brave_screenshot" src="https://github.com/user-attachments/assets/30865a8b-eba4-4554-9ddd-81a65fe59d4f" />


### License:

Apache 2.0 License.
