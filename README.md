# Kisah Si Heker Sial

> *Honeypot Intelligence Report — disajikan dalam format komik investigasi.*
> Oleh **masgus**

Komik web yang merekonstruksi 7 hari aktivitas seorang attacker di honeypot — lengkap dengan timeline serangan, korelasi fingerprint (audioFP, GPU, timezone), dan ironi kecil di tiap panel.

## Live

https://agussang.github.io/

## Stack

- HTML/CSS/JS murni — tanpa framework
- Fonts: Bangers, Comic Neue, JetBrains Mono (Google Fonts)
- Background OST: cyberpunk electronic dari [archive.org](https://archive.org) (CC license)
- Responsive: desktop, tablet, iPhone (≥320px)

## Struktur

```
agussang.github.io/
├── index.html      ← komik utama (panel timeline)
├── 404.html        ← halaman 404 bertema terminal
├── favicon.svg     ← (opsional) ikon
└── README.md
```

## Deploy

Auto-deploy dari branch `main` via GitHub Pages. Edit lokal → `git push` → live ~1 menit.

## Lisensi

Konten © 2026 masgus. Musik OST tetap mengikuti lisensi asli kreator di archive.org.
