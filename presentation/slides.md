---
theme: ./mathema-2023
defaults:
  layout: "default-with-footer"
title: 'ideavim'
occasion: "SENECA 2024"
occasionLogoUrl: "./images/logo-seneca24.png"
company: "MATHEMA GmbH"
presenter: "Patrick Drechsler"
contact: "patrick.drechsler@mathema.de"
info: |
  ## IdeaVim
canvasWidth: 980
layout: cover
transition: slide-left
mdc: true
download: true

src: ./pages/00-title.md
---

---
src: ./pages/01-intro.md
---

---

## Ported version of VIM

---

## Integration in Jetbrains IDE

- Plugin
- configuration file
- toggle

---

## Basic VIM features present by default

- import of `.vimrc`

---

## Override Jetbrains key bindings with Action keyword

- resolve conflicts between vim and Jetbrains:

```txt
sethandler <C-h> a:vim
```

- Use `<Action>` keyword:
```txt
" Jump between methods
nmap [[ <Action>(MethodUp)
nmap ]] <Action>(MethodDown)
```

---

## Plugins

- `Plug` or `set` syntax:

```txt
set highlightedyank
Plug 'machakann/vim-highlightedyank'
```

