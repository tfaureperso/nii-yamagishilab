---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "[Dec. 20] Textless Phrase-Structure Induction from Visually-Grounded Speech"
subtitle: ""
summary: ""
authors: [Cheng-I Jeff Lai]
tags: [talks]
categories: []
date: 2022-12-18T23:29:53+09:00
lastmod: 2022-12-18T23:29:53+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

title: "[Dec. 20] Textless Phrase-Structure Induction from Visually-Grounded Speech"
date: 2022-12-19
image:
  focal_point: 'top'

---

We study phrase structure induction from visually-grounded speech without intermediate text or text pre-trained models. The core idea is to first segment the speech waveform into sequences of word segments, then induce phrase structure based on the inferred segment-level continuous representations. To this end, we present the Audio-Visual Neural Syntax Learner (AV-NSL) that learns non-trivial phrase structure by listening to audio and looking at images, without ever reading text. Experiments on SpokenCOCO, the spoken version of MSCOCO with paired images and spoken captions, show that AV-NSL infers meaningful phrase structures similar to those learned from naturally-supervised text parsing, quantitatively and qualitatively. The findings in this paper extend prior work in unsupervised language acquisition from speech and grounded grammar induction, and manifest one possibility of bridging the gap between the two fields.
