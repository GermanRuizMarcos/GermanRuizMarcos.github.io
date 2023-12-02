---
title: "Guess who?"
layout: post
tag:
- AI
- MIR
- classification
image: https://gerumar.github.io/assets/images/composers.png
headerImage: true
projects: true
description: "Guess who?"
category: project
author: gerumar
externalLink: false
---

<p style='text-align: justify;'>The goal of this project was to build a system to automatically tag classical audio recordings with their composer.</p> 

<p style='text-align: justify;'>I built my own 800-piece dataset, which included eight different composers from different periods: <em>baroque</em> (J.S. Bach and A.L. Vivaldi), <em>classical</em>  (F.J. Haydn, W.A. Mozart and L. van Beethoven) and <em>romanticism</em>  (F. Chopin, F. Mendelssohn and F. Liszt). The audio clips were all transformed into 30-second 44.1kHz mono wav clips using the Sound eXchange tool.</p>  

<p style='text-align: justify;'>Based on MIREX’s similar projects from 2014-2016, the audio features extracted by the system include:</p>  

- flatness, 
- roll-off, 
- centroid, 
- flux, 
- energy, and 
- MFCCs. 

<p style='text-align: justify;'>Using WEKA’s Support Vector Machine, the system was capable of accurately tagging nearly 60% of the dataset.</p> 

[Check it out](https://musicinformationretrieval.wordpress.com/category/audio-tag-classification-clas sical-composer/) here.
