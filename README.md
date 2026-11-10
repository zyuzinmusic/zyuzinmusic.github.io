# Zyuzin Music – Online MusicXML Player

**Zyuzin Music** is a browser-based application for viewing and playing musical scores in MusicXML format. It combines music notation rendering with audio playback to make digital sheet music accessible directly from a web browser.

**Live application:** https://zyuzinmusic.github.io/

## Features

- **MusicXML score rendering:** Display musical notation in the browser.
- **Audio playback:** Listen to compositions using browser-based audio.
- **Instrument selection:** Select General MIDI instruments for playback.
- **Playback controls:** Play, pause, and stop music.
- **Music score navigation:** Follow playback through the displayed score.
- **Music library:** Select available MusicXML compositions from the online collection.
- **Multiple file formats:** Load `.xml`, `.musicxml`, and `.mxl` files where supported.

## Technologies

The application uses:

- **JavaScript** – application logic and playback coordination.
- **OpenSheetMusicDisplay (OSMD)** – rendering MusicXML scores.
- **OSMD Audio Player** – music playback integration.
- **Web Audio API** – browser-based audio processing and playback.
- **SoundFont Player** – General MIDI instrument sounds.
- **GitHub Pages** – hosting and deployment.

## How to Use

1. Open the [Zyuzin Music Player](https://zyuzinmusic.github.io/).
2. Select a composition from the available music library.
3. Wait for the score to load.
4. Select an instrument if desired.
5. Use the playback controls to listen to the composition while following the displayed notation.

## Running Locally

Clone the repository:

```bash
git clone https://github.com/zyuzinmusic/zyuzinmusic.github.io.git
```

Open the project directory:

```bash
cd zyuzinmusic.github.io
```

Start a local HTTP server, for example:

```bash
python -m http.server 8000
```

Open the application:

```text
http://localhost:8000/
```

A local HTTP server is recommended instead of opening `index.html` directly because browser security restrictions can affect JavaScript resource loading.

## MusicXML

MusicXML is a standard format for representing musical notation. It supports musical elements such as notes, rests, chords, measures, instruments, and other score information.

Zyuzin Music uses MusicXML to display and play musical compositions.

## Author

**Mikhail Zyuzin**  
Zyuzin Technologies

Website: https://zyuzinmusic.github.io/

Some compositions have been created, arranged, or edited by Mikhail Zyuzin.

## Acknowledgments

This project uses open-source music software libraries, including:

- [OpenSheetMusicDisplay (OSMD)](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay)
- [OSMD Audio Player](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay)

See the respective project repositories for licensing and attribution information.


