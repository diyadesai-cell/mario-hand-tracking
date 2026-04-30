# 🍄 mario-vibe
### *controllers are so 2020 💀*

```
    ██╗    ██╗████████╗███████╗    ██████╗ ██╗ ██████╗
    ██║    ██║╚══██╔══╝██╔════╝    ╚════██╗██║██╔═████╗
    ██║ █╗ ██║   ██║   █████╗       █████╔╝██║██║██╔██║
    ██║███╗██║   ██║   ██╔══╝      ██╔═══╝ ██║████╔╝██║
    ╚███╔███╔╝   ██║   ██║         ███████╗██║╚██████╔╝
     ╚══╝╚══╝    ╚═╝   ╚═╝         ╚══════╝╚═╝ ╚═════╝
```

> bro said "what if mario but ur hand is the controller" and actually built it 🤌

[![made by](https://img.shields.io/badge/made%20by-%40dii.codes-8338ec?style=for-the-badge)](https://instagram.com/dii.codes)
[![no controller](https://img.shields.io/badge/controller-not%20needed%20💀-ff006e?style=for-the-badge)]()
[![built different](https://img.shields.io/badge/built-different%20🍄-06ffa5?style=for-the-badge)]()

---

## 🤯 wait what is this

a **gesture-controlled 3D Mario** that runs in your browser  
no install. no controller. no cap.  
just your hand and a webcam and a poor sleep schedule

**your hand literally IS the controller.**

```
✋ move hand left/right  →  mario runs
🤌 pinch fingers         →  mario jumps  
✊ make a fist           →  mario DASHES at 2.5x speed
```

---

## 🔥 features (ngl this goes hard)

```
🧱  lego mario character — chunky. iconic. him.
🌅  day/night cycle — 6 phases. dawn to night. cinematic.
🏙️  neon city skyline — glows at night. unreal.
☁️  parallax clouds + hills — it's giving depth
🍄  infinite procedural world — pipes goombas coins forever
🎵  8-bit music — nintendo lawyers don't look here
📹  floating draggable webcam — built for the reel fr
⚡  runs at 60fps — optimized. no lag. smooth like butter.
💾  fully offline — zero CDN zero internet needed
```

---

## 🚀 run it (it's actually easy i promise)

> use **Chrome**. mediapipe said so. not me.

**step 1** — clone it
```bash
git clone https://github.com/YOUR_USERNAME/mario-vibe.git
cd mario-vibe
```

**step 2** — serve it (pick one)

```bash
# VS Code → right click index.html → Open with Live Server ✅ easiest

# OR python
python -m http.server 8080
# then open localhost:8080
```

**step 3** — allow camera, show hand, go crazy 🤌

> ⚠️ won't work from file:// — needs a local server bc mediapipe said so

---

## 📁 what's inside

```
mario-vibe/
├── 📄 index.html           ← the whole game. one file. no build step.
├── 📚 libs/
│   ├── three.min.js        ← Three.js r128 (offline)
│   └── mediapipe-hands/    ← hand tracking (offline)
│       ├── hands.js
│       └── *.tflite        ← the AI magic
└── 📖 README.md            ← ur reading it rn
```

yes the entire game is one HTML file  
yes that's unhinged  
yes it works perfectly  

---

## 🛠️ tech stack

| thing | what it does |
|-------|-------------|
| **Three.js r128** | makes the 3D world go brrr |
| **MediaPipe Hands** | sees ur hand in real time |
| **Web Audio API** | 8-bit sounds that slap |
| **Vanilla JS** | no react. no next. just vibes. |
| **1 HTML file** | that's it. that's the stack. |

---

## 🌅 the world is actually insane

- **6 day/night phases** — dawn → morning → noon → sunset → dusk → night
- **lego mario** — round yellow head, hat with stud, chunky legs, he's so real
- **infinite level** — pipes, platforms, goombas, coins spawn forever
- **floating webcam** — draggable PiP shows ur hand skeleton in neon green
- **memory safe** — GPU cleaned up properly, no lag after 10 mins

---

## 🗺️ what's coming (roadmap aka my sleep debt)

- [ ] ⭐ star power — rainbow lego mario + invincible mode
- [ ] 🦇 night enemies — bats replace goombas at night
- [ ] 🏆 high score — saved to localStorage
- [ ] 📱 moving platforms — more chaos
- [ ] 👐 two player — both hands = two characters (unhinged idea)

---

## 😭 the origin story

```
day 1   → "i'll make a simple mario game"
day 2   → added hand tracking
day 3   → added day/night cycle
day 4   → added lego character
day 5   → added floating webcam
day 6   → fixed 47 bugs
day 7   → posted the reel and went to sleep
```

---

## 👨‍💻 author

**@dii.codes** on instagram  
we build different here 🍄  
follow for more unhinged projects

---

## 📄 license

MIT — use it, break it, make it yours  
just don't forget where u found it 🤌

---

<div align="center">

### ⭐ star this if it made u go 🤯

*"POV: it's 2030 and controllers don't exist anymore"*

**built by [@dii.codes](https://instagram.com/dii.codes)**

</div>
