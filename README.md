# Petpet

The lifetime book for your pet. Private, forever yours.

A quiet, private iOS app to remember every page of your pet's life — kept on
your iCloud, not on social feeds. Coming early 2027.

- 🌐 Live site: https://petpet-app.pages.dev
- 📱 iOS app: in development · [join the waitlist](#)

---

## About this repository

This is the public source of the Petpet marketing website. Plain HTML + CSS, no
build step. GitHub Pages serves this repo's root.

The iOS app source lives in a separate private repository.

## Layout

```
.
├── index.html             Hero · vs-Instagram · 4-shot gallery · pricing · waitlist
├── css/style.css          Single stylesheet · system font · light/dark
├── assets/                iPhone screenshots used on the home page
├── privacy/index.html     Privacy Policy
├── support/index.html     Support: FAQ + contact
├── favicon-32.png         Browser tab favicon
├── icon-192.png           Android / PWA
└── apple-touch-icon.png   iOS home screen bookmark
```

## Local preview

```sh
python3 -m http.server 8765
```

Then open http://localhost:8765/.

## Waitlist

The waitlist form posts to Buttondown. No tracking, no analytics beyond
Buttondown's built-in subscriber count.

## License

Website content and copy © Petpet. Code is MIT-licensed if you want to adapt
the layout for your own pre-launch page.
