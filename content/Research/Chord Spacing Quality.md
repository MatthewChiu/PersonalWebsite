---
title: 2020 – Chord Spacing Quality
tags:
  - research
  - fourierTransform
  - "#timbre"
---
## [Chord Spacing and Quality: Lessons from Timbre Research](https://kb.osu.edu/server/api/core/bitstreams/829f5615-a471-46e2-a09d-b9a03a793d16/content)
### [Video](https://www.youtube.com/watch?v=smqI_kqZmpM) 
(the video is a different presentation covering much of the same material; please cite the proceedings article below)
```python
class CoAuthor
	def __init__(self, name):
		self.name = "Noah Kahrs"
```
### Format (When): Where
* Proceedings (2020) – [Future Directions of Music Cognition](https://kb.osu.edu/server/api/core/bitstreams/829f5615-a471-46e2-a09d-b9a03a793d16/content)
* Presentation (2020) – The Society for Music Theory
* Presentation (2020) – The Society for Music Theory, Math Interest Group
	* *Navigating the P-DFT Model: Subject-Data Correlations*
* Presentation – Music Theory Society for New York State

### TL;DR
Although chords are often represented by pitch-class (chroma) content in computational research, chord spacing is often a more salient feature. This paper addresses this disparity between models and cognition by extending the discrete #fourierTransform (DFT) theory of chord quality from pitch-classes to pitches. In doing so, we note a structural similarity between music theory’s chord quality and audio engineering’s timbral #cepstrum: both are DFTs, performed in the pitch or frequency domains, respectively. We thus treat chord spacing as a hybrid of pitch-class and timbre.

To investigate the potential benefits of the DFT on pitch space (P-DFT), we perform two computational experiments. The first explores the P-DFT model theoretically by correlating chord distances calculated with a pitch-class model against those calculated with spacing. The second compares P-DFT estimations of chord distances against listener responses (Kuusi, 2005). Our results show that spacing is a salient feature of chords, and that it can be productively described by timbre-influenced methods

### Additional Materials
[We designed a web app so anyone can calculate the P-DFT.](https://mattchiu.com/Pdft/pDFT.html)

[Here is the code](https://colab.research.google.com/drive/1o81GaWX-wvQsczaXjfHT1llxJJJSm_nX?usp=sharing) in #python