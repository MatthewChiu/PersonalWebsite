---
title: 2025 – Visual Features of Sheet Music
tags:
  - research
  - machineLearning
  - embeddings
  - corpus
  - "#artificialIntelligence"
---
## Visual Features of Sheet Music Using Autoencoders

### Format (When): Where
* Presentation (2025): **International Conference on Computational and Cognitive Musicology**
### Dataset
I collected sheet music from 7 musical periods, 3 composers from each period. Pieces are separated by composer, and are split into individual pages as jpgs. A minimum of 30 pages of music was ensured for each composer. The dataset includes 1,302 pages of music from 101 pieces. To train the model, I isolated 5 random (448x448 px) samples from each image (meaning there are 6,510 samples)—see below. To ensure samples were not predominantly white, I used a whiteness threshold (.9) to exclude samples which have a mean pixel value considered too white. 

Because I included popular music and scans that are not in the public domain, I am choosing not to publicly share the dataset—I am happy to give access to anyone who would like to see it or use it for research purposes.

| **Styles**            | **7 :** (Baro., Class., Rom., Impress., Rag., Tin-Pan, Pop/Rock) |
| --------------------- | ---------------------------------------------------------------- |
| **Composers/Artists** | **21** (3 from each style)                                       |
| **Pages**             | **1302** (min 30 from each)                                      |
| **Pieces**            | **101**                                                          |
| **Samples**           | **6,510**: 5 (448 x 448) samples from each score.                |


![[Pasted image 20250913104221.png|100]]![[Pasted image 20250913104328.png|99]]![[Pasted image 20250913104349.png|97]]
### Model Architecture


### Training



### Visual features


### Classification



### TL;DR
Chords don't always act the same, they change based on context: for example, a C major triad typically acts one way in C major key and another in F major. What about between styles and composers? Drawing on techniques from #machineLearning and #naturalLanguageProcessing, I derive numerical representations for chords based on their use in different styles. 

Studying representations from classical styles correlate with claims frequently made in music theory. In a rock style... not so much.

[Here's the accompanying code](https://colab.research.google.com/drive/1wSmPVDjnJIql7DifdTvUwsOj1Q-NcY2j?usp=sharingz) in #python.