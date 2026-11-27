# KeyBPM

**See the key, BPM and tuning of whatever your computer is playing, live.**

Play a track in Spotify, YouTube, SoundCloud, your DJ software or DAW, and KeyBPM shows:

- 🎹 **Key + Camelot code**, e.g. `F#m · 11A`, plus the next most likely key
- 🥁 **BPM**, to a tenth of a beat, with ½× / 2× correction buttons
- 🎚️ **Tuning (A=)**, e.g. `A = 432 Hz`. Detuned beats and samples are handled, and the key is corrected for the track's own tuning.

It starts listening as soon as it opens and resets on its own between tracks. Nothing is recorded or saved.

## Download

Get the latest version from **[Releases](../../releases/latest)**:

| | File | Requires |
|---|---|---|
| Windows | `KeyBPM-Windows.zip` | Windows 10 / 11 (64-bit) |
| Mac | `KeyBPM-Mac.zip` | macOS 14.2 or newer, Intel or Apple Silicon |

## First launch

The app isn't signed by a paid developer certificate yet, so your computer warns you the first time:

- **Windows:** "Windows protected your PC" → **More info** → **Run anyway**
- **Mac:** click **Done**, then System Settings → Privacy & Security → **Open Anyway**. Allow system audio recording when asked.

## Notes

- Windows: KeyBPM listens to your default playback device. DJ software running in ASIO or exclusive mode bypasses Windows audio, so KeyBPM can't hear it.
- Give it 5–10 seconds per track.
