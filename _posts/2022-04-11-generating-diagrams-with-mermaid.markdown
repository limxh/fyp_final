---
layout: post
title: "Generating Diagrams with Mermaid"
date:   2022-04-11 14:33:23 +0800
tags: ["plugins", "jekyll"]
mermaid: true
---

## Sample 1

<div class="mermaid">
graph LR
    A --- B
    B-->C[Happy]
    B-->D(Sad);
</div>


## Sample 2

<div class="mermaid">
    graph TD
      B[peace]
      B-->C[fa:fa-ban forbidden]
      B-->D(fa:fa-spinner);
      B-->E(fa:fa-camera-retro perhaps?);
</div>