---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral fellow in [Susztak Lab](https://www.med.upenn.edu/susztaklab) in the Departments of Genetics and Medicine at the University of Pennsylvania.
Since 2007, my research has mainly focused on the genomics and epigenomics of complex human diseases by developing scalable machine-learning methods and integrating 
multimodal genomic and epigenomic data. A central objective of my study is to understand the genetic basis and epigenetic regulation of complex human diseases, 
by integrating genome-wide association studies with transcriptomic and epigenomic analyses. 
These studies have answered population genetic questions about epigenome-mediated heritability and causal gene prioritization via epigenome.

Research
======
Genetic architecture and epigenetic regulation of kidney disease (Postdoctoral research, 2018 - present)
------
* I discovered that epigenome (DNA methylation) explains a larger fraction of heritability than gene expression by integrating large scale GWAS, eQTL and meQTL datasets. To further identify disease-causal genes, I proposed a multi-stage prioritization strategy and prioritized >500 kidney disease genes, including <em>SLC47A1<em>, whose causal role was defined in knockout mice model and in human individuals carrying loss-of-function variants. (Liu et al., 2022 [Nature Genetics](https://www.nature.com/articles/s41588-022-01097-w); [Project page](https://susztaklab.com/GWAS/index.php); [Github](https://github.com/hbliu/Kidney_Epi_Pri)).
* In my latest study, I expanded kidney function GWAS with a larger number of individuals. To explore the regulatory potential of genetic variants, I investigated features of genetics variants by integrating bulk and single-cell multi-omic datasets. These results substantially improved the informativeness of disease mechanisms at GWAS loci (Liu et al. In preparation).
* To explore epigenetic regulation in kidney development, we profiled DNA methylation by Whole-Genome Bisulfite Sequencing in mouse and human fetal kidneys, and demonstrated essential functions of DNA methylation in decommissioned fetal enhancers linking to kidney disease (Guan, Liu et al. 2020 [JASN](https://jasn.asnjournals.org/content/31/4/765); Liu et al. In preparation). These studies highlighted locus-specific convergence of genetic, epigenetic, and developmental elements in kidney disease development.
* To identify cell types causally associated with kidney disease, we generated single-nucleus transposase-accessible chromatin with sequencing (snATAC-seq), single-cell RNA sequencing (scRNA), and spatially resolved transcriptomics in mouse and human kidneys. The analysis of these single-cell resolution datasets illustrated the crucial roles of kidney cells (e.g., proximal tubule cells) and cell type-specific genes (e.g., SLC47A1) in kidney injury and fibrosis. (Liu et al., 2022 [Nature Genetics](https://www.nature.com/articles/s41588-022-01097-w); Sheng,…,Liu et al., 2021 [Nature Genetics](https://www.nature.com/articles/s41588-021-00909-9); Miao,…, Liu et al. 2021, [Nature Comms](https://www.nature.com/articles/s41467-021-22266-1); Doke,…, Liu et al., 2021 [JCI](https://www.jci.org/articles/view/141801); Dhillion,…, Liu et al., [Cell Metabolism](https://www.sciencedirect.com/science/article/pii/S1550413120306069?via%3Dihub); Amin,…, Liu et al. 2022 [BioRxiv](https://www.biorxiv.org/content/10.1101/2022.10.24.513598v1)).

Tissue-specific and disease-critical epigenetic regulatory elements (Prior research, 2007 - 2017)
------
* To identify tissue-specific epigenetic regulatory elements, I developed a series of bioinformatic software, such as SMART for de novo identifying tissue/cell-specific methylated regions from whole genome bisulfite sequencing data (Liu et al. 2016 [NAR](https://academic.oup.com/nar/article/44/1/75/2499653); [Project page](http://fame.edbc.org/smart/)); QDMR for identifying differentially methylated regions from array-based methylation data (Zhang, Liu et al. 2011 [NAR](https://academic.oup.com/nar/article/39/9/e58/1254752); [Project page](http://fame.edbc.org/qdmr/)); QDCMR for identifying differential chromatin regions from ChIP-seq data (Liu et al. 2013 [Sci. Rep.](https://www.nature.com/articles/srep02576); [GitHub](https://github.com/hbliu/QDCMR)).
* Leveraging these bioinformatic tools and large-scale epigenome data, I identified tissue-specific epigenetic regulatory elements, including DNA methylation, histone modifications, super-enhancers, and long non-coding RNAs, and explored their roles in mammalian development and human diseases (Liu et al. 2016 [NAR](https://academic.oup.com/nar/article/44/1/75/2499653); Liu et al. 2014 [Database](https://academic.oup.com/database/article/doi/10.1093/database/bat084/2633757); Liu et al. 2013 [Sci. Rep.](https://www.nature.com/articles/srep02576); Xu, Liu et al. 2019 [Cell Death & Disease](https://www.nature.com/articles/s41419-019-2137-5); Xiong,…, Liu et al. 2017 [NAR](https://academic.oup.com/nar/article/45/D1/D888/2605746); Wei,…, Liu et al. 2016 [NAR](https://academic.oup.com/nar/article/44/D1/D172/2503054); Lv, Liu et al. 2013 [NAR](https://academic.oup.com/nar/article/41/22/10044/2438380); Lv, Liu et al. 2012 [NAR](https://academic.oup.com/nar/article/40/D1/D1030/2903287); Zhang, Liu et al. 2011 [NAR](https://academic.oup.com/nar/article/39/9/e58/1254752); Zhang, Lv, Liu et al. 2010 [NAR](https://academic.oup.com/nar/article/38/suppl_1/D149/3112313)). 


<!-- 
Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
 -->
