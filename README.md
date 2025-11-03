# 🥁 JavaScript Drum Kit

A simple and interactive **drum kit web app** built using **HTML**, **CSS**, and **JavaScript**.  
Press the corresponding keys on your keyboard to play different drum sounds!

---

## 🎵 Features
- Play drum sounds using keyboard keys (A–L)
- Smooth transition animations when keys are pressed
- Instant sound replay using `audio.currentTime = 0`
- Lightweight — no external libraries required

---

## 🎹 Key Mapping

| Key | Sound     |
|-----|------------|
| A   | Clap       |
| S   | Hi-hat     |
| D   | Kick       |
| F   | Open Hat   |
| G   | Boom       |
| H   | Ride       |
| J   | Snare      |
| K   | Tom        |
| L   | Tink       |

---

## ⚙️ How It Works
1. Each key has an HTML element with a `data-key` attribute matching its keyboard key code.
2. When a key is pressed:
   - The JavaScript `keydown` event triggers the `playSound()` function.
   - The corresponding audio file plays.
   - The key element briefly gets a “playing” CSS class for visual feedback.
3. When the animation ends, the class is removed using a `transitionend` event listener.

---

## 🚀 Getting Started

### 1. Clone this repository
```bash
git clone https://github.com/yourusername/js-drum-kit.git
cd js-drum-kit
