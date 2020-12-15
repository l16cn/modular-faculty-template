# auto-faculty-package

## On Overleaf

- Click on "Menu" and choose one of the following files as the "Main document" to compile:
    + `1_cover.tex` (cover letter)
    + `2_cv.tex` (CV)
    + `3_research.tex` (research statement)
    + `4_teaching.tex` (teaching statement)
    + `5_publication.tex` (list of publications)
    + `10_references.tex` (list of reference contacts)

## Locally

- Change the first line (root) in `main.tex` to one of the main documents

## Files

- Root
    + `definitions.tex`: acronyms (see [my LaTeX package](https://github.com/l16cn/latex-package) for details)
    + `library.tex`: university-specific and position-specific information
    + `references.bib`: example bibliography file
    + `resume.cls`: custom resume class for CV
    + `yu_*.sty`: custom style files (see [my LaTeX package](https://github.com/l16cn/latex-package) for details)
- `fig/`: figure directory
- `slide/`: presentation directory
- `snippets/`: text snippets
    + `bio_unique_background.tex`: background snippet
    + `cv_*.tex`: example snippets for CV
    + `list_presentations.tex`: example snippet of publications for CV
    + `list_publications.tex`: example snippet of presentations for CV
    + `research_opening.tex`: opening paragraph used by both the cover letter and the research statement
    + `research_topic.tex`: snippet of an individual proposed research topic
