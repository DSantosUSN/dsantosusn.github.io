---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# Welcome!

## About Me
I am currently a bioinformatics research tech at the La Jolla Institute of Immunology where I work in the Peters Lab. My primary focus has been on how we can improve ways of estimating expression of HLA genes from bulk RNA-Seq data. In my free time, I enjoy playing video games, programming, hiking, drinking beer and hanging out with my cat.

## Projects
### ARC
ARC (antigen receptor classifier) is a Python module used to classify unknown protein sequences as immune related molecules (MHC, T Cell Receptor, Antibody). It accomplishes this task by using hidden markov models trained from IMGT data. ARC lives on the IEDB github [here](https://github.com/iedb/arc)
### HLAQuant
HLAQuant is a pipeline designed to quantify HLA allele specific expression from bulk RNA-Sequencing data. Currently, the pipeline is unavailable pending publication, however, a Python module is ready for distribution.

## Publications
**Nelson et al. (2014)**. Complete Genome Sequence for the Fusarium Head Blight Antagonist Bacillus amyloliquefaciens Strain TrigoCor 1448. Genome announcements. 2. [10.1128/genomeA.00219-14.](https://mra.asm.org/content/2/2/e00219-14) 

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>