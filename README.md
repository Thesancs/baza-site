# BAZA® — Site

Site institucional/comercial da BAZA Brands (Campinas — SP). HTML/CSS/JS estático, sem build.

- `index.html` — Home (11 seções) + estudos de caso via `#slug`
- `assets/img/` — fotos do portfólio em WebP (`-sm` = versão mobile)
- `assets/video/` — vídeo da hero (desktop 16:9 e mobile vertical) + posters

O vídeo da hero roda em autoplay (muted/loop/playsinline) e é carregado em lazy loading: o HTML não tem `src`; o script injeta a fonte depois do `load`, pausa fora da tela e respeita `prefers-reduced-motion` e economia de dados.

Para trocar o vídeo, substitua `assets/video/hero-desktop.mp4` e `assets/video/hero-mobile.mp4` (e os posters).
