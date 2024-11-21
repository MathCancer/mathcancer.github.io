---
---

# Lab Website Template

Paul Macklin's MathCancer Lab is based in the 
[Department of Intelligent Systems Engineering](https://engineering.indiana.edu/) at the 
[Luddy School of Informatics, Computing and Engineering](https://luddy.indiana.edu/) at 
[Indiana University-Bloomington](https://bloomington.iu.edu/). 
Our lab works to develop data-driven computational systems that can help engineer the behavior of multicellular systems, especially in cancer and tissue engineering.

To advance these aims, our lab is leading developments in the following areas of strength:

* Simulation of 3-D tissue environments
* Simulation of 3-D multicellular systems
* Simplified specification of multicellular simulation models 
* Estimation of cell phenotype parameters from experiments
* Data standards for multicellular biology, and data sharing
* Specific applications in breast cancer, liver cancer, tissue engineering, and other areas

We bring together multidisciplinary teams of clinicians, biologists, modelers, computer scientists, engineers and others to help build and apply these technologies. Together, we're building the digital infrastructure to turn today's science fiction into tomorrow's engineering reality.

{% include section.html %}

{%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%}

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
