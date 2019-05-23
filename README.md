# Introducing the Framework for Parsing Plenary Protocols (R package frappp): Rmarkdown / html slides

## Background

The R Markdown files at the top level of this repository are the basis for generating html slides available at a GitHub Pages:

  - The [English version of the slides](https://polmine.github.io/frappp_slides/slides_en.html) has been presented at the [ParlaFormat Workshop](https://www.clarin.eu/event/2019/parlaformat-workshop) on a proposed standard format for parliamentary data (May 23/24 2019, Amersfoort, The Netherlands).
  - An earlier [German version](https://polmine.github.io/frappp_slides/slides_de.html) has been presented at the [3-Länder-Tagung](https://www.dvpw.de/kongresse/3-laender-tagungen/) of the Swiss, Austrian and German associations for political science.


## Usage and browser compatibility

The html slides that are available online (German/English) have been generated from the R Markdown files at the top level in this repository (slides_de.Rmd/slides_en.Rmd). 

To build the slides, an installation of the following (data) packages is necessary:

- frappp (not yet publicly available)
- trickypdf
- DiagrammeR
- GermaParl (with downloaded corpus)
- UNGA (with downloaded corpus)
- ParisParl (with downloaded corpus)
- PopParl (with downloaded corpus)
- AustroParl (with downloaded corpus)

Please note that we have seen Firefox crash due to the embedded pdf documents. The best user experience may be achieved using Chrome or Safari.


Andreas Blaette, March, 23 2019
