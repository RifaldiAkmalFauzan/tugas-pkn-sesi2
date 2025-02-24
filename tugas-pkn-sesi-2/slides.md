---
# theme configuration
theme: default
title: Tugas PKN-Sesi-2
titleTemplate: '%s - Tugas PKN'

# presentation info
info: |
  # Sistem Pemerintahan Indonesia
  Presentasi Kelompok TI24B - Universitas NusaPutra

# author info
author: Ahmad Hasan Maki
authorId: 20240040032

# global style
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false

# transitions
transition: slide-left
mdc: true

# enable presenter mode
presenter: true

# enable download
download: true

# favicon
favicon: '/img/logo-university.png'

layout: intro
---

# terbentur, terbentur, terbentur. <br> terbentuk<br> --datuk ibrahim tan malaka

---

## src: ./pages/opening.md

---

## src: ./pages/timeline.md

---

## src: ./pages/pascareformasi.md

---

## src: ./pages/ordebaru.md

---

src: ./pages/reformasi.md
layout: full

---

<!-- Global style overrides -->
<style>
.slidev-layout {
  h1 {
    @apply text-3xl font-bold mb-4;
  }

  p {
    @apply text-lg leading-relaxed;
  }
}
</style>
