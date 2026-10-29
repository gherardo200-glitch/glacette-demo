# Fonti e licenze dei video

I video di mare vengono da Pexels (licenza Pexels: uso commerciale libero, attribuzione non obbligatoria,
https://www.pexels.com/license/). Originali scaricati in HD/4K e ricodificati con ffmpeg (H.264, senza audio).

| File | Origine | Uso |
|---|---|---|
| `riva-sotto.mp4` (1080x676, 10,5 s, ~1,9 MB) | https://www.pexels.com/video/top-view-of-breaking-waves-on-a-beach-10650850/ (Pexels, ID 10650850). Ritaglio del fotogramma, ruotato di 180 gradi (sabbia in alto, mare in basso) e loop con dissolvenza incrociata di 1,5 s | Footer: la riva vista dall'alto, sabbia in alto e schiuma che sale dal fondo |
| `mare-notte.mp4` (540x960, 5 s, ~1,2 MB) | https://www.pexels.com/video/top-view-of-flowing-water-in-sea-12339462/ (Pexels, ID 12339462), loop con dissolvenza di 1 s | Mare dietro al secchiello (home) |
| `hero-brina.mp4` (1280x720, 7 s, ~0,9 MB), `hero-brina.webm` (VP9, ~0,5 MB), `hero-brina-mobile.mp4` (720x1280, 7,4 s, ~0,6 MB) | Video di brand GENERATO CON GEMINI (Google), originale `gemini_generated_video_BAE45D2E.MP4` fornito da Gherardo (non modificato). Tagliato dai 3,0 s (via il secchiello in acciaio), senza audio, +faststart. Per mobile c'e' un secondo video verticale 9:16 nativo, `gemini_generated_video_1E0627B9.MP4` (anche questo generato con Gemini, fornito da Gherardo, originale non modificato), tagliato dai 2,625 s (via il secchiello) e senza audio | Hero della home (parte una volta e si ferma sul logo) |
| `scrub-provvisorio.mp4` (1280x720, 6 s, ~5 MB) | Generato con ffmpeg da `public/img/harmony41-hero-tavolara.jpg` (foto Glacette) | PROVVISORIO: da sostituire con il video turntable vero |

I file `poster-*.webp` sono il primo fotogramma di ciascun video.

Clip Pexels scartate per il footer (guardate e non usate): 12480992, 6696973 (rocce e impronte), 11627817,
35016325, 4196184 (sabbia scura).

`hero-mobile-riga-alta.png` e `hero-mobile-riga-bassa.png` (720x1): prima e ultima riga di pixel dell'ultimo fotogramma
di `hero-brina-mobile.mp4`. Riempiono la fascia sopra e sotto quando la hero mobile si allontana per far stare intero il
logo (vedi Hero.jsx). Se cambia il video vanno rigenerate dal suo ultimo fotogramma.
