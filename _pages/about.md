---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD researcher at the Biomedical Imaging Group Rotterdam ([BIGR](https://bigr.nl/)) at [Erasmus MC](https://www.erasmusmc.nl/en/) under the supervision of [Dr. Theo van Walsum](https://scholar.google.com/citations?user=pBz9JUEAAAAJ&hl=en), [Pro. Wiro J. Niessen](https://scholar.google.com/citations?user=jmKtufcAAAAJ&hl=en), [Pro. Aad van der Lugt](https://scholar.google.nl/citations?user=3Xp-E0UAAAAJ&hl=en), and [Prof. Danny Ruijters](https://www.tue.nl/en/research/researchers/danny-ruijters). At the moment, I am visiting the [Martinos Center for Biomedical Imaging](https://www.martinos.org/), MGH, [Harvard Medical School](https://hms.harvard.edu/) under the supervision of [Dr. Adrian Dalca](http://www.mit.edu/~adalca/). Earlier, I've completed my Bachelors from [Shandong University](https://en.sdu.edu.cn/) and Masters from [TU Munich](https://www.tum.de/en/), and gained industrial experience as a software engineer at [ASML](https://www.asml.com/en) and a research scientist at [Philips Research](https://www.philips.com/a-w/about/innovation/research.html).

I started doing research on image and video processing. In the recent past I have primarily focused on applied research in medical image analysis within the healthcare sector. My contributions center on the development of innovative methodologies and their clinical applications in the field of cardiovascular healthcare.

Current research interests: *Medical AI, signal/image/video processing, spatio-temporal learning, stroke, cardiovascular imaging*

Awards & Distinctions
======
* 2023:        German [DAAD AInet Fellow](https://www.daad.de/en/the-daad/postdocnet/details-and-application/). <br>
* 2023:        Receipt of IEEE EMBS Best Paper Award. <br>
* 2022 - 2023: Receipt of the [KNAW Academy Van Leersum Grant](https://www.knaw.nl/toekenningen-knaw-van-leersum-beurs-2022) for international collaboration. <br>

Selected Publications
======
  {% assign selected_pubs = site.publications | reverse %}
  {% assign permalinks = "/publication/2023-05-24-swineangio, /publication/2022-01-19-perforation, /publication/2021-04-01-autotici" %}
  <ul>{% for post in selected_pubs %}
      {% if permalinks contains post.permalink %}
        {% include about-single-publication.html %}
      {% endif %}
    {% endfor %}
  </ul>

  <a href="./publications">More publications</a>