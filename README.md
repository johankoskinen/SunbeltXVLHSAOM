# SunbeltXVLHSAOM
<!-- PROJECT LOGO -->



<!-- OVERVIEW -->
## Overview of the workshop

The workshop is built around a set of slides and a set of RMarkdown files, with accompanying data sets, that you will find here


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started



### Context

By network data, we will assume data where we have observations on binary tie-variables among a fixed set of nodes. In a typical dataset, network ties will be elicited through name-generators,[[1]](#1) such as

> Anongs the people in your organisation, list the people that you go to for advice

There are many other ways in which to collect and `operationalise' network ties. Here we will not deal with network inference such as inferring causal graphs or other network represenations

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### R-Prerequisites

There are plenty of tutorials and introductions to network analysis in R and we refer, for example to Borgatti et al (2022)[[2]](#2) for a comprehensive treatment (see also the accompanyhing online supplementary material)

No particular R-skills are expected. You should be able to download the RMarkdown files and run them locally. The RMarkdown files will read any data straight from [https://raw.githubusercontent.com/johankoskinen/CSunbeltXVLHSAOM
/main/data/](https://raw.githubusercontent.com/johankoskinen/SunbeltXVLHSAOM
/main/data/).

Examples of loading and formatting network data is provided in
```sh
Markdowns/Data-Formatting.Rmd
```

You will find it in  [CHDH-SNA/Markdowns](https://github.com/johankoskinen/SunbeltXVLHSAOM
/tree/main/RCode)

No fancy R-wrappers will be used and the code is written entirely in base R and [Quick-R](https://www.statmethods.net/)
should be a sufficient source of help outside of Googling package specific issues. For the SAOM part of the workshop (sessions 2-4) the repository 
[https://www.stats.ox.ac.uk/~snijders/siena/](https://www.stats.ox.ac.uk/~snijders/siena/) contains all the resources you will ever need.

<h3 align="center"><a href="https://www.stats.ox.ac.uk/~snijders/siena/"><img src="images/rsienalogo.png" alt="R" width="100" height="100"></a></h3>

You *will*, however, need to come with a laptop with R and R-studio installed. In addition, you will want to install the packages
* sna
  ```sh
  install.packages(sna)
* network
  ```sh
  install.packages(network)  
  
* RSiena
  ```sh
  install.packages(RSiena)
  
 If you need to update your version of R, a handy guide is provided [here](https://www.linkedin.com/pulse/3-methods-update-r-rstudio-windows-mac-woratana-ngarmtrakulchol) 

 Please note that RSiena is no longer maintained on CRAN. Now the latest version fo RSiena and other packages is found here: [GitHub/RSiena](https://github.com/stocnet/rsiena/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Install <a href="https://cran.r-project.org/"><img src="images/Rlogo.svg" alt="R" width="25" height="25"></a> (R version 4.2.1 (2022-06-23) may be required)
- [x] Install <a href="https://posit.co/download/rstudio-desktop/"><img src="images/RStudio-Logo-Flat.png" alt="R" width="88.35" height="31.025"></a>
- [ ] Download `sienaBayes-A.1.Rmd` 
- [ ] Explore RMarkdown by
    - [ ] Stepping through code
    - [ ] Knit to html or pdf for future reference
- [ ] Consult slide pack

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

<img src="images/koskinen_johan.jpg" alt="Me" width="205.2" height="254.4">

Johan Koskinen - [@drjohankoskinen](https://twitter.com/drjohankoskinen) - johan.koskinen@stat.su.se


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## References
<a id="1">[1]</a> 
Robins, G. (2015).
Doing Social Networks Research: Network Research Design for Social Scientists.
Los Angeles: Sage.

<a id="2">[2]</a> 
Borgatti, S. P., Everett, M. G., Johnson, J. C., & Agneessens, F. (2022).
Analyzing Social Networks Using R.
Sage.
