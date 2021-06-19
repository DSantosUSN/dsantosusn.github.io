---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# Welcome!

## About Me
I am currently a bioinformatician at the La Jolla Institute for Immunology where I work in the Peters Lab.
Professionally I am interested in all aspects of computational immunology, but more specifically T Cell Receptor and MHC biology. Outside of work you can find me playing video games (especially old school RPGs), brewing beer, or watching anime. 
## Projects
### TCRMatch
TCRMatch is a method of determining TCR similarity in an alignment free manner. It was published in Frontiers in Immunology [here](https://www.frontiersin.org/articles/10.3389/fimmu.2021.640725/full) and can be downloaded [here](https://github.com/iedb/tcrmatch). It is optimized for speed and written in C++.
### ARC
ARC (antigen receptor classifier) is a Python module used to classify unknown protein sequences as immune related molecules (MHC, T Cell Receptor, Antibody). It accomplishes this task by using Hidden Markov Models trained from IMGT data as well as curated BLAST databases. ARC lives on the IEDB github [here](https://github.com/iedb/arc).

## Publications
**Chronister, Crinklaw* et al. (2021)**. TCRMatch: predicting T-Cell receptor specificity based on sequence similarity to previously characterized receptors. Frontiers in Immunology. [10.3389/fimmu.2021.640725](https://www.frontiersin.org/articles/10.3389/fimmu.2021.640725/full). *Co-first author and very proud :-)

**Chandra et al. (2021)**. Promoter-interacting expression quantitative trait loci are enriched for functional genetic variants. Nature Genetics. 53, 110-119. [10.1038/s41588-020-00745-3](https://www.nature.com/articles/s41588-020-00745-3)

**Nelson et al. (2014)**. Complete Genome Sequence for the Fusarium Head Blight Antagonist Bacillus amyloliquefaciens Strain TrigoCor 1448. Genome announcements. 2. [10.1128/genomeA.00219-14.](https://mra.asm.org/content/2/2/e00219-14) 

<!---
## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
--->