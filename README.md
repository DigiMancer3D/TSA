# Technical Synth Machine

**A powerful, fully self-contained web-based synthesizer** built with HTML, CSS, and the Web Audio API. Designed for techno, dubstep, glitch, electro, 808/rap beats, leads, basses, pads, stabs, and experimental sound design.

No installation required — just open the single HTML file in any modern browser. Turn it into a native-like desktop app on **Kubuntu / Ubuntu** in minutes.

## Quick Start on Kubuntu / Ubuntu

1. Save your HTML file to a permanent location, for example:
   `~/Applications/Technical-Synth/TSA.2.html`

2. Create the desktop entry:
   ```bash
   mkdir -p ~/.local/share/applications
   nano ~/.local/share/applications/technical-synth.desktop
   ```

3. Use one of the following methods for the content based on your preferred browser to use for the output.

A. **(UnGoogled-Chromium)** Paste the following content:
   ```bash
   [Desktop Entry]
   Name=Technical Synth Machine
   Comment=Professional web synthesizer
   Exec=ungoogled-chromium --app="file:///home/YOURUSERNAME/Applications/Technical-Synth/TSA.2.html" --class=TechnicalSynth --window-size=920,720 --disable-features=Translate
   Icon=applications-multimedia
   Type=Application
   Categories=AudioVideo;Music;Audio;
   Terminal=false
   StartupNotify=true
   ```

B. **(Chromium)** Paste the following content:
   ```bash
   [Desktop Entry]
   Name=Technical Synth Machine
   Comment=Professional web synthesizer
   Exec=chromium-browser --app="file:///home/YOURUSERNAME/Applications/Technical-Synth/TSA.2.html" --class=TechnicalSynth --window-size=920,720 --disable-features=Translate
   Icon=applications-multimedia
   Type=Application
   Categories=AudioVideo;Music;Audio;
   Terminal=false
   StartupNotify=true
   ```


4. Replace YOURUSERNAME with your actual username and save the file.

5. Make it executable and refresh the menu:
   ```bash
   chmod +x ~/.local/share/applications/technical-synth.desktop
   update-desktop-database ~/.local/share/applications
   ```


Now you can launch Technical Synth Machine directly from the KDE menu or desktop shortcut like a native application.


---


## Features

- Multi-layer formant synthesis with humming, breathiness, jitter & shimmer

- 20+ factory presets + 12 Blank Gap presets (0.1s–3s) for perfect timing

- Per-sound 3-band EQ + Global 3-band EQ

- Dedicated Filter (LP/HP/BP) with cutoff, resonance and drive

- Arpeggiator per sound (BPM-synced or free, Up/Down/Up-Down/Random, octaves, gate)

- Enhanced LFO with 5 waveforms (sine, triangle, saw, square, sample & hold) and BPM sync

- Sidechain compression simulation for classic pumping

- Full Sequencer with save/load/export and audio render to WAV

- Microphone recording + audio file import

- Complete project save/load (.tsm files)

- Fine-tune +/- buttons on every slider


## Controls Overview


### Master Section

- Compressor (Threshold, Ratio, Makeup)

- Delay (Time, Feedback)

- BPM + BPM Sync

- Sidechain Amount – Classic pumping effect

- Global 3-band EQ


### Per-Sound Layers

- Core: Volume, Pan, Reverb, Pitch, ADSR, Hold, Fade In/Out, Loop Gap, Transition

- Filter: Type (LP/HP/BP), Cutoff, Resonance, Drive

- Arpeggiator: Enable, Rate Mode, Pattern, Octaves, Gate

- LFO: Assign, Waveform, Rate Mode (Free/Synced), Depth

- Formants: 6 bands (F1–F6) with Frequency + Gain

- Textures: Humming, Breathiness, Jaw Jitter, Pitch Jitter, Amplitude Shimmer

- Effects: Distortion, Chorus, Noise Gate


### Sequencer

- Step-based triggering per sound

- Loop with adjustable gap

- Save/Load/Export full projects and render to WAV


#### Tips

- Click any slider label to show Reset options

- Use +/- buttons for precise adjustments

- Blank presets are ideal for creating tight rhythmic gaps

- Enable BPM Sync to lock everything to tempo


---

## License
Free and open-source. Feel free to modify and share.

## Credits

##### Designed by 3Douglas [Z0M8I3D](https://x.com/z0m8i3d) Pihl
##### Coded by Grok [xAI](https://grok.com)


---

###### Made for the electronic music community.
###### &nbsp;&nbsp;&nbsp;Enjoy creating!
