Modular Faculty Application (LaTeX Templates)
=====

## Introduction

It takes a lot of time preparing a job application package. So for my own applications, I created a "modular" template in LaTeX to satisfy the following two objectives.

- To assemble content modules for an application. For instance, I may want to include two out of three prepared research topics for one position, but another two for a different position.
- To eliminate "hard-coded" repetitions. If certain content appears in more than one place, I can edit the corresponding module, and the updates will appear in all the places that link to that module.

Doing so not only has saved me lots of time, but it also helps me avoid inconsistency caused by hard-coding. Now, I want to make this template publicly available.

In the `.tex` files, I removed as much information that is specific to me as possible. However, I think it more helpful for some files (e.g., the CV template) to retain such information. All information specific to me can also be found on my personal website.

## On Overleaf

- [Modular Faculty Template](https://www.overleaf.com/latex/templates/modular-faculty-template/ypdtgsfsshkw) is now available as an Overleaf template
- Click on "Menu" and choose one of the following files as the "Main document" to compile:
    + `1_cover.tex`: cover letter
    + `2_cv.tex`: CV
    + `3_research.tex`: research statement
    + `4_teaching.tex`: teaching statement
    + `5_edi.tex`: equity, diversity, and inclusion statement
    + `6_references.tex`: list of reference contacts
    + `7_publication.tex`: list of publications
    + `8_beamer.tex`: job talk with animation
    + `8_handout.tex`: job talk without animation (handout mode)

## Locally

- Change the first line (root) in `main.tex` to one of the main documents

## Directory

- `definitions.tex`: acronym definitions and glossary shortcuts (see [my LaTeX package](https://github.com/l16cn/latex-package) for details)
- `library.tex`: university-specific and position-specific information
- `references.bib`: example bibliography file
- `resume.cls`: custom resume class for CV
- `yu_*.sty`: custom LaTeX style files (see [my LaTeX package](https://github.com/l16cn/latex-package) for details)
- `fig/`: figure directory
- `slide/`: presentation directory
    + `example_slide.tex`: sample slide with animation, bullet points, an in-text citation, and a figure
    + `research_tree.tex`: example research tree slide (extracted from [my personal website](https://yuluo.me))
- `module/`: module directory
    + `bio_unique_background.tex`: background module
    + `cv_*.tex`: example modules for CV
    + `edi.tex`: equity, diversity, and inclusion module for the equity, diversity, and inclusion statement abd the teaching statement
    + `list_presentations.tex`: list of publications module for CV
    + `list_publications.tex`: list of presentations module for CV
    + `research_opening.tex`: opening paragraph module used by both the cover letter and the research statement
    + `research_topic.tex`: proposed research topic module

## Log

#### 2020-12-30

- Added an Introduction

#### 2020-12-21

- [Modular Faculty Template](https://www.overleaf.com/latex/templates/modular-faculty-template/ypdtgsfsshkw) is now available as an Overleaf template
- This README is the new default main file
