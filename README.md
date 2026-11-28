# Stillwave

**An audio player for musicians**. It looks minimal, but it's built for working with your own tracks, demos and stems.

**[Download the latest version](https://github.com/merelleyneqt-sys/stillwave-releases/releases/latest)**

## What it does

### Notes inside the file
Pin notes to exact moments of a track. They are saved **inside the audio file itself**, so when you send the file to someone, they open it in Stillwave and see your notes on the waveform, on Mac and Windows alike. Works with MP3, WAV, AIFF, FLAC and M4A.

### Stem player
Open a folder of stems and play them all in perfect sync.
- Mute, solo, pan and volume for every stem
- Save Changes writes each stem's volume and pan into its file
- A waveform and peak level for every stem
- Integrity check: finds silent, clipped, unreadable or too short files and mismatched sample rates

### Cover art by drag and drop
Drop a picture onto the player, from a folder or straight from a browser. It becomes the track's cover and is written into the file's metadata. Your other tags stay as they were, and the audio isn't re-encoded.

### Auto name
One button renames the track to a clean template and fills in its metadata:

`Artist - Title (G#m_120BPM)`

Title, artist, key and BPM are written into the file's tags.

### And more
- **Key and BPM detection**, with Camelot codes
- **Trim** without re-encoding, keeping tags, cover and notes (FLAC and M4A: Mac only)
- **Fades** in and out with four curves, written into the file
- **Mono button** to check how the mix sounds in mono
- **Loudness (LUFS)** of the whole track
- **Detailed stereo waveform**: left channel on top, right below, with zoom
- **Gapless loop** of the whole track or the part you're trimming
- **Precise volume** in 0.1 dB steps
- **Automatic updates**: the app tells you when a new version is out

## Download

| System | File |
| --- | --- |
| Mac (Apple Silicon, macOS 15+) | `.dmg` |
| Windows, most PCs | `x64.exe` |
| Windows on ARM | `arm64.exe` |
