---
theme: seriph
background: /img/opening-background.jpg
title: Tugas PKN-Sesi-2
info: |
  # presentasi kelompok TI24B
class: text-center
drawings:
  persist: false
Author: Ahmad Hasan Maki
transition: slide-left
mdc: true
mermaid: true
src: ./pages/opening.md
---

---
layout: cover
background: /img/slide-timeline.jpg
class: 'text-white text-center px-17'
transition: slide-up
src: ./pages/timeline.md
---

---
layout: cover
background: /img/transisi-to-ordebaru.jpg
class: 'text-white text-center px-14'
transition: slide-up
---

<v-click>

# 22 Februari 1966 - 21 Mei 1998
</v-click>

---
layout: cover
class: 'text-white text-center px-17'
transition: slide-up

---

<div v-click="[2, 4]" v-motion
  :initial="{ x: -50 }"
  :enter="{ x: 0 }"
  :leave="{ x: 50 }"
>
  Shown at click 2 and hidden at click 4.
</div>
---
