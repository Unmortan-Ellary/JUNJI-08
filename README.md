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
- Support 20 Patch Presets.
- `Left Mouse Click` to Load Patch, `Right Mouse Click` to Save current Patch.
- `Export` Saves current Patch as `*.patch` file (Hold `ALT` to Export it to Clipboard).
- `Import` Loads `*.patch` files (Tries to Load it from Clipboard first).

8. **Miscellaneous:**
- Keyboard velocity support via `Vel TO Amp` Knob.
- Two `128-Step` Sequencers with Automation.
- Virtual Keyboard with Octave selection.
- Wide Stereo Voice `Spread` Function.
- `Glide` From Note to Note Function.
- `Transpose` Note Function.

### Sequencers Guide:

1. **WIP**
- WIP.

### License:

Apache 2.0 License.
