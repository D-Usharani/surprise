# 💕 Happy Birthday — An Interactive Friend Experience

> *A cinematic, game-style birthday surprise website built with pure HTML, CSS & JavaScript.*

---

## 🌐 Live Demo

👉 **[View the Website](https://yourusername.github.io/your-repo-name)**
*(Replace with your actual GitHub Pages link)*

---

## 💖 About This Project

This is a handcrafted birthday surprise website made with Friend — no frameworks, no libraries, just pure HTML, CSS and JavaScript. It takes your special person through a cinematic, interactive experience they'll never forget.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎬 **Cinematic Intro** | Animated pulsing rings, glowing title, starfield background |
| 🎮 **Friend Quiz Game** | 5 romantic questions with score tracking, correct/wrong animations & firework bursts |
| 📸 **Polaroid Gallery** | 6 real photos displayed as tilted polaroids that pop in one by one |
| 💌 **Friend Letter** | A heartfelt letter with cinematic glow effects |
| 🎂 **Live Countdown** | Real-time countdown ticker to June 16 |
| 🎆 **Fireworks & Particles** | Click anywhere to trigger hearts & fireworks |
| 🌹 **Floating Petals** | Continuous rose petal & heart animations |
| ✨ **Custom Cursor** | Glowing pink cursor with ring trail |

---

## 📁 File Structure

```
📂 repo/
  ├── index.html   ← The entire website (one file)
  ├── m1.png       ← Photo 1
  ├── m2.jpg       ← Photo 2
  ├── m3.png       ← Photo 3
  ├── m4.png       ← Photo 4
  ├── m5.jpg       ← Photo 5
  ├── m6.png       ← Photo 6
  └── README.md    ← This file
```

---

## 🚀 How to Host on GitHub Pages

1. **Fork or create** a new repository on [github.com](https://github.com)
2. **Upload** `index.html`, all photo files, and `README.md` to the repo
3. Go to **Settings → Pages**
4. Under *Source*, select **main branch** → click **Save**
5. Your site will be live at:
   ```
   https://yourusername.github.io/your-repo-name
   ```
6. Share the link — and watch them smile 💕

---

## 🛠️ Customisation

### Change the name / date
Open `index.html` and edit the hero section:
```html
<h1 class="intro-title">Happy Birthday</h1>
<p class="intro-sub">to the one who has my whole heart</p>
<p class="intro-date">16 · JUNE · FOREVER YOURS</p>
```

### Change photos
Swap out `m1.png` – `m6.png` with your own images. Update the captions in the JS section:
```js
const photos = [
  { src: 'm1.png', caption: 'Us, always 💕', rot: '-2.5deg' },
  // ...
];
```

### Change quiz questions
Edit the `questions` array in the `<script>` section of `index.html`.

### Change the Friend letter
Find the `.letter-body` section in `index.html` and update the `<p>` paragraphs.

---

## 💻 Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

- **Zero dependencies** — no frameworks, no npm, no build tools
- **Single file** — the entire experience lives in one `index.html`
- **Fully responsive** — works on mobile & desktop

---

## 📸 Screenshots

> *Add screenshots of your website here once it's live!*
> You can drag and drop images directly into the GitHub README editor.

---

## ❤️ Made With Friend

*Because some people deserve more than just a text message on their birthday.*

---

<p align="center">Made with 💕 for someone very special · June 16</p>
