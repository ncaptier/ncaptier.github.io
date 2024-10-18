---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<div class="wordwrap">You can also find a more detailed version of my CV <a href="https://ncaptier.github.io/files/cv_captier.pdf">here</a>.</div>
<br>

{% include base_path %}

Education
======
* 2020-2024 - **Ph.D in Computer science**, Institut Curie, PSL University, Paris, France      
  *Multimodal analysis of radiological, pathological, and transcriptomic data for the prediction of
immunotherapy outcome in Non-Small Cell Lung Cancer patients*
* 2019-2020 - **Master MVA (Mathematics, Vision, Learning), M.Sc**, Ecole Normale Supérieure, Paris-Saclay, France
* 2016-2020 - **Diplôme d'ingénieur de l'Ecole polytechnique**, Ecole polytechnique, Palaiseau, France
* 2013-2016 - **B.Sc. in Physics & B.Sc. in Mathematics**, Sorbonne University, Paris, France

Experience
======
* 10/2020-06/2024: **Institut Curie, PhD student**
  * PhD funded by the PaRis Artificial Intelligence Research InstitutE (PRAIRIE)
  * Multidisciplinary research project for the multimodal prediction of immunotherapy response in lung cancer (funded by Fondation ARC: 600,000€)
  * Supervisors: Irène Buvat & Emmanuel Barillot

* 04/2020-09/2020: **Institut Curie, Research Intern**
  * Development of inference methods for unraveling associations between radiomic and transcriptomic features for lung cancer patients
  * Supervisors: Irène Buvat & Emmanuel Barillot

* 04/2019-08/2019: **Institute for Applied Mathematics, Bonn University, Research Intern**
  * Development of a stochastic model for the interplay of melanoma cells and immmune cells under immunotherapy
  * Prize of the "Mathematical Modeling and Biodiversity" Chair of Ecole polytechnique
  * Supervisor: Anton Bovier
  
Skills
======
* Languages - French (Native) - English (Fluent)
* Coding - Python (pytorch, scikit, pandas), R, Java, HTML, LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service activities
======
* 2020-Present - Peer-reviewing for *Bioinformatics advances*, *BMC Bioinformatics*, and the *Journal of Nuclear Medicine* (JNM)