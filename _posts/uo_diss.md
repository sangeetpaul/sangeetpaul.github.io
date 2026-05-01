---
title: 'UO Dissertaion'
date: 2025-07-30
permalink: /posts/uo-diss/
author_profile: false
tags:
  - UO
---

If you want to use Overleaf, it already has a template:
https://www.overleaf.com/latex/templates/uothesis-memoir/nnwbzcpckqhd

If you don't have a paid Overleaf account, you'll eventually run out of compilation time. In that case, you might want to use an offline LaTeX editor and use this template:
https://github.com/unofficial-uoregon-dissertation-formats/unofficial-uoregon-grad-school-dissertation-latex-markdown-apa-format

VS Code is a good alternative that can compile LaTeX locally on your device, hence you're only limited by your device, your imagination, and your mental health. You can also keep your thesis synced with a git repo so that you never lose your work.

To write your thesis in VS Code, follow these steps:
1. Make sure VS Code is installed
2. Install TeX Live: https://www.tug.org/texlive/
3. Install extension LaTeX Workshop in VS Code:
https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop
4. Download the aforementioned git repo as zip:
https://github.com/unofficial-uoregon-dissertation-formats/unofficial-uoregon-grad-school-dissertation-latex-markdown-apa-format
5. Extract zip
6. Open folder `latex_files` in VS Code
7. In `settings.json`, add as _first_ entry to `latex-workshop.latex.recipes`: `{"name": "make", "tools": ["make"]}`
8. Again, in `settings.json`, add as _first_ entry to `latex-workshop.latex.tools`: `{"name": "make", "command": "make", "args": [], "env": {}}`
9. Time to test. Edit author's name in `cover.tex`. Save. It should auto-build.

![Congratulations](/images/congratulations.gif)