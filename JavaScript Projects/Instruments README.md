# Multi-Instrument Virtual Player

A responsive web-based musical instrument simulator allowing users to play piano, guitar, and drums through an intuitive interface. This project showcases my skills in web audio API implementation, interactive UI design, and JavaScript event handling.
![image](https://github.com/user-attachments/assets/c6002056-e137-4013-a579-6660eae64179)

## Features

- **Multiple Virtual Instruments**: Play piano, guitar, and drums in a single application
- **Keyboard Controls**: Use your computer keyboard to play notes and sounds
- **Audio Synthesis**: High-quality audio generation using the Web Audio API
- **Interactive UI**: Visual feedback when playing instruments
- **Customization Options**:
  - Adjustable volume control
  - Toggle key labels display
  - Select individual instruments or play all simultaneously

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Web Audio API
- Bootstrap 5
- Google Material Icons

## How It Works

The application uses the Web Audio API to generate instrument sounds in real-time:

- **Piano**: Synthesizes sine wave oscillators with appropriate frequencies for each note
- **Guitar**: Uses sawtooth waveforms with realistic decay to simulate plucked strings
- **Drums**: Combines various oscillator types and noise generators to create different percussion sounds

## Usage

### Piano
- Play white and black keys with your mouse or use keyboard keys (a, w, s, e, d, f, etc.)
- Spans across multiple octaves for extended range

### Guitar
- Six virtual strings corresponding to standard guitar tuning (E, A, D, G, B, E)
- Play using number keys 1-6 or by clicking on strings

### Drums
- Includes kick, snare, hi-hat, tom, crash, and ride cymbal
- Play using Q, Z, X, C, V, B keys or by clicking on drum pads

## Future Enhancements

- Add recording and playback functionality
- Implement additional instruments
- Create shareable compositions
- Add preset rhythms and backing tracks
- Mobile touch optimization

## Installation

Simply clone the repository and open `index.html` in your browser:

```
git clone https://github.com/yourusername/multi-instrument-player.git
cd multi-instrument-player
open index.html
```

## License

MIT License

## Acknowledgements

- Web Audio API documentation
- Bootstrap framework
- Music theory resources for proper note frequencies