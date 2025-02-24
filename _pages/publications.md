---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

"[PRISM: Simple And Compact Identification and Signatures From Large Prime Degree Isogenies](https://eprint.iacr.org/2025/135)", with Andrea Basso, Giacomo Borin, Wouter Castryck, Maria Corte-Real Santos, Riccardo Invernizzi, Antonin Leroux, Frederik Vercauteren, and Benjamin Wesolowski. PKC 2025.

"[Radical 2-isogenies and cryptographic hash functions in dimensions 1, 2 and 3](https://eprint.iacr.org/2024/1732)", with Sabrina Kunzweiler, Tomoki Moriya , Christophe Petit, Giacomo Pope, Damien Robert, Miha Stopar, and Yan Bo Ti. PKC 2025.

"[POKÉ: A Compact and Efficient PKE from Higher-dimensional Isogenies](https://eprint.iacr.org/2024/624)", with Andrea Basso. EUROCRYPT 2025. 

"[SQIsign2D-West: The Fast, the Small, and the Safer](https://eprint.iacr.org/2024/760)", with Andrea Basso, Pierrick Dartois, Luca De Feo, Antonin Leroux, Giacomo Pope, Damien Robert, and Benjamin Wesolowski. ASIACRYPT 2024.

"[An Algorithmic approach to (2,2)-isogenies in the Theta Model and Applications to Isogeny-based Cryptography](https://eprint.iacr.org/2023/1747)", with Pierrick Dartois, Giacomo Pope, and Damien Robert. ASIACRYPT 2024.

"[FESTA: Fast Encryption from Supersingular Torsion Attacks](https://eprint.iacr.org/2023/660)”, with Andrea Basso, and Giacomo Pope. ASIACRYPT 2023. 

"[Towards a Quantum-Resistant Weak Verifiable Delay Function](https://eprint.iacr.org/2023/1197)", with Thomas Decru, and Antonio Sanso. LATINCRYPT 2023. 

"[A Direct Key Recovery Attack on SIDH](https://eprint.iacr.org/2023/640)", with Chloe Martindale, Lorenz Panny, Giacomo Pope, and Benjamin Wesolowski. EUROCRYPT 2023. **(Best Paper Honourable Mention)**

"[A Review of Mathematical and Computational Aspects of CSIDH Algorithms](https://www.worldscientific.com/doi/10.1142/S0219498825300028?srsltid=AfmBOoq4pHDxS0NyrehniM6GUnxwbcaz0nIb_oShNcXIfnajiVxFEVnD)", with Marzio Mula, and Federico Pintore. Journal of Algebra and Its Applications, Special Issue on Recent Advancements in Coding Theory & Cryptography. (2023) 

"Mathematical and Computational aspects of CSIDH-based Algorithms", with Federico Pintore. Algebra For Cryptography, Aracne Editrice, Collectio Ciphrarum 1. (2021)

Preprints
======

"[An attack on SIDH with arbitrary starting curve](https://eprint.iacr.org/2022/1026)", with Chloe Martindale. (2022)



<!-- ---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %} -->

<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->





