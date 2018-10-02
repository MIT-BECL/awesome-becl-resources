<!--- use this to make TOC https://ecotrust-canada.github.io/markdown-toc/ -->

<div align="center">
    <img width="500" height="350" src="media/awesomelogo.png" alt="commawesome">
    <br>
    <br>

<br>

<div align="center">


Tools, tips, & resources compiled by fellows of the [MIT Biological Engineering Communication Lab](http://mitcommlab.mit.edu/be/)

<div align="left">

# Getting started
Below is a list of resources compiled for BE Communication Lab fellows relevant to undergraduate, graduate students, and postdocs at MIT. Although there are some MIT-specific resources, this list is also relevant to any STEM student/researcher.

The MIT BE Communication Lab resources are also stored within this repository and are highlighted within the list below. If you have any questions, email us at `becl@mit.edu`.

This list compiles resources to transform data into a clear message through:
- **data analysis and visualization,**
- **figure design,**
- **writing and reference management,**
- **design tools and resources,**
- **professional resources.**

It also includes **resources for reproducibility** and miscellaneous tools for biological engineering research (e.g. plasmid design, flow cytometry analysis, next-generation sequencing).

---

# Contents

- [Legend](#legend)
- [Computing](#computing)
  * [Programming Languages](#programming-languages)
  * [Computing Clusters at MIT](#computing-clusters-at-mit)
- [Data Visualization](#data-visualization)
  * [General Data Viz. Resources](#data-visualization-theory-and-guides)
  * [Plotting Tools](#plotting)
    + [Python Plotting](#python-plotting)
    + [R Plotting](#r-plotting)
    + [Other Plotting tools](#other-plotting-tools)
- [Reproducible Analysis](#reproducible)
  * [General Principles](#general-principles)
  * [R Workflows](#r-workflows)
  * [Python Workflows](#python-workflows)
- [Writing](#writing)
  * [TeX/LaTex](#tex-latex)
  * [Markdown](#markdown)
  * [Citations and Reference Management](#citations-and-reference-management)
- [Figures](#figures)
  * [Drawing](#drawing)
  * [Image Manipulation](#image-manipulation)
- [Design Tools & Resources](#design-tools---resources)
  * [Color](#color)
  * [Fonts & Typography](#fonts---typography)
  * [Icons](#icons)
  * [Images](#images)
- [Poster Design](#poster-design)
  * [Poster Design Tools](#poster-design-tools)
  * [Poster Templates](#poster-templates)
  * [Poster Galleries](#poster-galleries)
- [Scientific Software](#scientific-software)
  * [Chemical Structures](#chemical-structures)
  * [Analytical Chemistry](#analytical-chemistry)
  * [Protein Structure Visualization](#protein-structure-visualization)
  * [Plasmid Editors](#plasmid-editors)
  * [Flow Cytometry](#flow-cytometry)
  * [Microscopy Analysis](#microscopy-analysis)
- [Unsorted Weblinks](#unsorted-weblinks)
- [Professional Resources](#professional-resources)
- [Miscellaneous & Unsorted](#miscellaneous---unsorted)

[License](#license)

## Legend

| Symbol | Meaning |
|:----------:|:-------:|
|:free:| no upfront cost|
|:unlock:| open source |
|:dollar: | small cost |
|:moneybag:| large cost|
|:package:| Computing Package |
|:books:| Resource |

---

## Computing

### Programming
*Students typical use the follow resources to analyze and plot data for class and research purposes.*

- [Python](https://www.python.org/) :free: :unlock: – general applicability, open-source; commonly used with [Anaconda](https://anaconda.org/), a package and environment manager

- [R](https://www.r-project.org/) :free: :unlock: - popular for bioinformatics, genomics, statistics; typically used with [RStudio](https://www.rstudio.com/) :free: using packages from [CRAN](https://cran.r-project.org/)

- [MATLAB](https://www.mathworks.com/products/matlab.html) :moneybag: - commercial computing environment offered at MIT for affiliates. See [Gnu Octave](https://www.gnu.org/software/octave/) for an open source :unlock: alternative.

- Other computing languages/platforms used include [Julia](https://julialang.org/) and  [Go](https://golang.org/), but their user bases are much smaller.

### Computing Clusters at MIT
*Computing clusters are available at MIT and affiliate institutions for use by students and non-affiliates.*  

- [Athena](https://ist.mit.edu/athena?category=19) – computing environment offering remote environments with pre-installed software and file storage

- [TIG](https://tig.csail.mit.edu/) - CSAIL group offering computing services

- [AWS](https://aws.amazon.com/), [Google Cloud](https://cloud.google.com/), [Microsoft Azure](https://azure.microsoft.com/en-us/) - commercially available services simple to setup with researcher funds

- [C3DDB](https://www.mghpcc.org/resources/computer-systems-at-the-mghpcc/c3ddb/) - Boston-wide resource for life science researchers

- [Koch Institute Bioinformatics & Computing Core](https://ki.mit.edu/sbc/bioinformatics/services) - offers a variety of cloud computing resources

- [McGovern Institute Core](https://mcgovern.mit.edu/technology/high-performance-computing-cluster) - Linux-based cluster offering storage and CPU/GPU performance

- Other institutes (e.g. Broad Institute) and groups offer internal computing resources, inquire directly to gain access

---

## Data Visualization

### Data Visualization Resources

-   [Trees, Maps, and Theorems: Effective Communication for Rational Minds by Jean-Luc Doumont](http://www.principiae.be/X0800.php) - The CommLab Bible
-   [http://serialmentor.com/dataviz/](http://serialmentor.com/dataviz/)
-   [https://datavizcatalogue.com/](https://datavizcatalogue.com/)
-   [http://www.cookbook-r.com/Graphs/](http://www.cookbook-r.com/Graphs/)
-   [https://python-graph-gallery.com/](https://python-graph-gallery.com/)
-   [https://www.data-to-viz.com/](https://www.data-to-viz.com/)

### Plotting Tools

#### Python Plotting

-   [matplotlib](https://matplotlib.org/) – the most popular plotting framework
-   Pandas - table management
-   bokeh – interactive web-based visualization
-   [seaborn](https://seaborn.pydata.org/index.html) – opinionated plotting framework for statistical visualizations
-   plotly – interactive web-based visualization
-   altair – straightforward visualization framework, biased towards statistical plotting
-   [Rpy2](http://rpy2.readthedocs.io/en/version\_2.8.x/) - use R code in jupyter notebook

#### R Plotting

-   ggplot2 – the most popular plotting framework
-   plotly – interactive web-based visualization
-   rbokeh – interactive web-based visualization (built as interface to Python version)
-   shiny – interactive charts, applications, and websites
-   visNetwork – network plotting
-   ggvis – similar to ggplot2, but can create rich, interactive plots
-   [reticulate](https://blog.rstudio.com/2018/03/26/reticulate-r-interface-to-python/) use python code in R markdown
-   [RStudio cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf)

#### Other Plotting tools

-   RAW – fast, easy graphs from Excel or CSV files
-   Graphpad Prism – stand-alone plotting program
-   Excel – the one and only
-   Datawrapper – fast, easy graphs from Excel or CSV files
-   Octave – Free version MATLAB
-   [WebPlotDigitiazer](https://automeris.io/WebPlotDigitizer/)

## Reproducible Analysis

### General Principles
- [Naming files and projects](https://speakerdeck.com/jennybc/how-to-name-files) :notebook:, a slide deck compiled by Jenny Bryan (@JennyBryan), software engineer at RStudio

### R workflows
- [drake](https://github.com/ropensci/drake) :package: – toolkit to build reproducible workflows that scale
- rapport
- knitr - allows to convert markdown, R, and plots/tables to html or PDF files, similar to Jupyter for python
- workflowr
- here - makes it easy for users to set directories and paths
- ROpenSci

### Python workflows
- [Crash course in reproducible research in Python](http://t-redactyl.io/blog/2016/10/a-crash-course-in-reproducible-research-in-python.html) :notebook:

## Writing

-   [Comparison of different text editors](https://pandoc-scholar.github.io/)

### TeX/LaTex

- [Rticles](https://github.com/rstudio/rticles)

### Markdown


-   [Pandoc](https://pandoc.org/) - for switching between .doc/.tex/.md/etc file types
-   Microsoft Word

### Citations and Reference Management

-   [Zotero](https://www.zotero.org/) :free: :unlock:
-   [Mendeley](https://www.mendeley.com/) :free:
-   EndNote :moneybag:
-   Papers :moneybag:
-   Readcube
-   Jabref


## Figures

### Drawing

-   Adobe Illustrator :moneybag: :moneybag:
-   [Inkscape](https://inkscape.org/en/) :free: :unlock:
-   Microsoft Powerpoint :hankey:
-   [Affinity Designer](https://affinity.serif.com/en-us/designer/) :moneybag:

### Image Manipulation

-   Adobe Photoshop :moneybag: :moneybag:
-   [Affinity Designer](https://affinity.serif.com/en-us/designer/) :moneybag:
-   [GIMP](https://www.gimp.org/) :free: :unlock: The GNU Image Manipulation Program
-   ImageJ/Fiji :free: :unlock:





## Design Tools & Resources

### Color

-   [ColorBrewer](http://colorbrewer2.org/) - web-based color palette tool with accessibility options ([R package](https://cran.r-project.org/web/packages/RColorBrewer/index.html))
-   [Palettable](https://www.palettable.io) - similar to ColorBrewer with customizable color schemes ([Python package](https://jiffyclub.github.io/palettable/))
-   [Adobe Color CC](https://color.adobe.com/create/color-wheel/) - select color schemes based on color wheel and color harmony
-   [Ggsci](https://nanx.me/ggsci/) - color themes inspired by scientific journals, science fiction, and media
-   [Viz-Palette](http://projects.susielu.com/viz-palette)
-   [GenZ Yellow](https://tul.imgix.net/content/article/gen-z-yellow.jpg?auto=format,compress&w=740&h=486&fit=crop&crop=edges) :trollface:
-   [Millenial Pink](https://i.guim.co.uk/img/media/d0105731685e5b2b3daecf2fa00c9affaba832f1/0_0_2560_1536/master/2560.jpg?width=620&quality=85&auto=format&usm=12&fit=max&s=264f8669796563668ae798cdc3073e35) :trollface:

### Fonts & Typography

-   [Butterick’s Practical Typography](https://practicaltypography.com/) - typography best practices
-   [Google Fonts](https://fonts.google.com/) - select from fonts based on characteristics
-   [Canva](https://www.canva.com/font-combinations/) - font combinations based on starter font
-   [Font Squirrel](https://www.fontsquirrel.com/) - downloadable fonts based on characteristics
-   [Neue Haas Grotesk](http://www.fontbureau.com/nhg/)

### Icons

-   [Noun Project](https://thenounproject.com/) - downloadable icons
-   [IcoMoon](https://icomoon.io/) - more icons

### Images

-   [Unsplash](https://unsplash.com/) - downloadable high-quality images


## Poster Design

### Poster Design Tools

-   Adobe Illustrator :moneybag: :moneybag:
-   [Inkscape](https://inkscape.org/en/)
-   Microsoft Powerpoint :hankey:
-   Adobe InDesign :moneybag: :moneybag:

### Poster Templates

- [null](link)

### Poster Galleries

- [null](link)



## Scientific Software

### Chemical Structures

- [ChemDraw](link)

### Analytical Chemistry

- [Mnova](mestrelab.com/software/mnova/)

### Protein Structure Visualization

- [Chimera](https://www.cgl.ucsf.edu/chimera/)
- [Pymol](https://pymol.org/2/)

### Plasmid Editors

- [ApE](http://jorgensen.biology.utah.edu/wayned/ape/) :free:
- [Benchling](https://benchling.com/) - a web-based plasmid editor and database :free:
- [Geneious](link) :moneybag:
- [SnapGene](link) :moneybag:


### Flow Cytometry

- [Flowjo](link) :moneybag: :moneybag:
- [Cytoflow](http://bpteague.github.io/cytoflow/) :free: :unlock:

### Microscopy Analysis

-   [CellProfiler](http://cellprofiler.org/)
-   [ImageJ](https://imagej.nih.gov/ij/)

## Unsorted Weblinks

-   BLAST
-   TCoffee
-   [MPI Bioinformatics Toolkit](https://toolkit.tuebingen.mpg.de/#/)
-   [HMMER](http://hmmer.org/)
-   ClustalOmega
-   GSEA
-   Weblogo
-   Pfam
-   Espript
-   Primer3
-   Ensembl




## Professional Resources

- [Github Personal Webpage Boilerplate](https://academicpages.github.io/)
- PhD/Post-Doctoral website examples
    + [https://jef.works/](https://jef.works/) (Harvard, Bioinformatics)
    + [https://www.nikhitasingh.com/](https://www.nikhitasingh.com/) (MIT Media Lab, AI)
    + [https://davidlazar.org/](https://davidlazar.org/) (MIT CSAIL, Computing)
    + [https://www.anishathalye.com/](https://www.anishathalye.com/) (MIT CSAIL, Computing)
    + [https://slowkow.com/](https://slowkow.com/) (Harvard, Immunogenomics)

## Miscellaneous & Unsorted



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [*MIT BECL*](https://github.com/MIT-BECL) has waived all copyright and related or neighboring rights to the compilation of this list, but not the resources included.
