---
title: "autognomus"
layout: post
tag:
- AI
- music generation
- tension
image: https://gerumar.github.io/assets/images/autognomus.png
headerImage: true
projects: true
description: "autognomus"
category: project
author: gerumar
externalLink: false
---

<p style='text-align: justify;'><em>autognomus</em>, as in <b>Au</b>tomatic <b>T</b>ension-<b>O</b>riented <b>G</b>e<b>n</b>erator <b>o</b>f <b>Mus</b>ic, is a Python-based system capable of generating tonal music that has long-term structure and that matches input tension profiles in real time. I developed autognomus as part of my PhD research project.</p> 

<p style='text-align: justify;'>I designed <em>autognomus</em> as a music generation system that consists of four sub-systems.</p>  


![Screenshot](https://gerumar.github.io/assets/images/architecture.png)

 <p style='text-align: justify;'><em>Themer</em>, the first sub-system, is responsible for the generation of a musical theme with a well-defined structure. <em>Arranger</em>, the second sub-system, is responsible for the generation of an accompaniment, for the original theme, that matches common voice-leading conventions <em>Developer</em>, the third sub-system, is responsible for the generation of new musical material based on the structure and hierarchical relations of the original theme. And <em>Morpher</em>, the fourth sub-system, responsible for the transformation of generated materials, according to the rules in Lerdahl’s <em>Model of Tonal Tension</em> and his <em>Generative Theory of Tonal Music</em>, so that the materials match input tension profiles in real time.</p>


[Check it out](https://doi.org/10.21954/ou.rd.15028599.v2) here.
