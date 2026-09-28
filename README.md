# Art Appreciation Web Blog — GROUP 3

A lightweight, static blog platform created as a collaborative academic project for *Art Appreciation* (BSIT 3-2, PUP Santa Rosa, Academic Year 2026-2027). This repository serves as a digital gallery and blog documenting our group's analyses, critiques, and local field observations.

* *Repository:* [Art-Appreciation-Blogsite](https://github.com/CharmanderTheGreat/Art-Appreciation-Blogsite)
* *Live Deployment:* [https://charmanderthegreat.github.io/Art-Appreciation-Blogsite/](https://charmanderthegreat.github.io/Art-Appreciation-Blogsite/)

---

## 👥 Group Members

* *[Luke Edward G. Schofield]*
* *[Albert Lawrence B. Robiñol]*
* *[Steven James P. Leosala]*
* *[Avryl Rohmer T. Marapoc]*
* *[Dwayne Lawrence SF. San Juan]*
* *[Nikko J. Agcaoili]*

---

## 📍 Image Documentation & Location Context

All photographic documentations, architectural captures, and on-site subject images featured across this blog were personally captured by the developers in and around *Santa Rosa, Laguna*, mainly in Nuvali and near the old museum by the Santa Rosa Plaza. These photographs highlight local landmarks, public art installations, architecture, and community aesthetics explored during our fieldwork.

---

## 🎨 Blog Content Overview

* *Public Art & Murals:* Critical breakdowns of local murals and art installations, highlighting color, composition, and emotional impact.
* *Sculpture & Monuments:* Field observations of physical sculptures and civic monuments located around Santa Rosa.
* *Architecture:* Evaluations of buildings and public spaces, looking at both their form and their function.

---

## 📝 Evaluation Framework

Each of the ten photographs is evaluated using the steps in evaluating art (Ragans, 2005):

1. *Description:* What is literally seen in the photograph.
2. *Analysis:* How the elements and principles of art are used.
3. *Interpretation:* The mood, message, or story behind the artwork.

Every photograph is also classified under one of four aesthetic theories: *Imitationalism*, *Formalism*, *Emotionalism*, or *Utilitarianism*, with a short explanation of why it fits.

---

## ♿ Accessibility Features (GEDSI)

The blog includes an accessibility panel (♿ button, bottom-right) to make the content easier to use for more people:

* *Read Aloud:* Text-to-speech using the browser's built-in Web Speech API. Each photo has its own 🔊 button, and the panel has a *Read Entire Page* option that reads the introduction, all photo evaluations, and the team section.
* *Color-Blind Mode:* Switches the accent colors to the Okabe-Ito color-blind-safe palette.
* *Font Size Controls:* `−`, `+`, and reset (↺) buttons with 3 text size levels.

Accessibility settings (font size and color-blind mode) are saved in the browser's localStorage, so they stay after a refresh.

---

## 🛠️ Built With

* *HTML5:* Semantic markup structure (all code consolidated in a single `index.html`).
* *Tailwind CSS (via CDN):* Responsive, utility-first styling with a dark aesthetic theme, plus custom CSS for animations and accessibility modes.
* *JavaScript (Vanilla):* Dynamic gallery rendering from a data array, step-by-step evaluation tabs, image lightbox, and accessibility features.
* *Google Fonts:* Cinzel and Plus Jakarta Sans.
* *GitHub Pages:* Static site hosting and deployment.

---

## 🗂️ Project Structure

```
Art-Appreciation-Blogsite/
├── index.html
├── README.md
└── images/
    ├── 1.jpg ... 10.jpg        # Artwork photographs
    └── mem1.jpg ... mem6.jpg   # Team member photos
```

---

## ✏️ Editing the Content

All photo entries live in the `artworks` array inside the `<script>` of `index.html`. Each entry has an image path, title, location, aesthetic theory, theory explanation, and the three evaluation steps (description, analysis, interpretation). Team member photos and names are in the *About the Team* section.

---

## 🚀 Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/CharmanderTheGreat/Art-Appreciation-Blogsite.git
   ```
2. Open the project folder:
   ```bash
   cd Art-Appreciation-Blogsite
   ```
3. Open `index.html` in your browser, or use an extension like VS Code Live Server.

> An internet connection is needed for Tailwind CSS and Google Fonts, since both load from a CDN.