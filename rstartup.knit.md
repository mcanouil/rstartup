---
title: '"Débuter" avec <i class = "fab fa-r-project"></i> ...'
pagetitle: '"Débuter" avec R'
subtitle: 'En Commençant par le Début ...'
author: 'Mickaël Canouil, *Ph.D.* (<a href = "http://m.canouil.fr/" target = "_blank"><i class = "fas fa-home"></i> m.canouil.fr</a>)'
institute: "_Inserm U1283 / CNRS UMR8199 / Institut Pasteur de Lille / Université de Lille_"
date: 'Mercredi 7 Octobre 2020 - 12 h 00 (CEST / UTC + 2)'
knit: (function(inputFile, encoding) rmarkdown::render(inputFile, encoding = encoding, output_file = "docs/index.html"))
output:
  xaringan::moon_reader:
    self_contained: true
    mathjax: null
    css: [assets/default.css, assets/fonts.css, assets/rlille.css]
    includes:
      in_header: assets/_scripts.html
    nature:
      highlightStyle: github
      highlightLines: true
      slideNumberFormat: | 
        <div class="progress-bar-container">
          <div class="progress-bar" style="width: calc(%current% / %total% * 100%);">
          </div>
        </div>
      ratio: "16:9"
      countIncrementalSlides: false
---
