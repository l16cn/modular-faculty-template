Modular Faculty Application (LaTeX Templates)
=====

## On Overleaf

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

#### 2020-12-21

- [Modular Faculty Template](https://www.overleaf.com/latex/templates/modular-faculty-template/ypdtgsfsshkw) is now available as an Overleaf template
- This README is the new default main file
