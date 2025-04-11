# markdown everything

## Intro
Some years ago I've decided to use markdown every time I could, memos, specs,
ADRs, documentation, decks, emails, etc. The need to generate different
displayable format, I've started using pandoc, a magical piece of software to
convert almost any format, after pandoc, with the incorporation of LaTeX
templates or the revel.js presentation framework, I've manage to generate PDFs,
and presentation decks.

## Why this repo?
The goal of this repo is to provide a cheatsheet, compile resources for this
workflow and some code snippets to generate the documents.

## Install
I'm maintaining this section just for Debian.

```bash
apt install pandoc \
            pandoc-filter-diagram \
            texlive-latex-extra \
            texlive-fonts-extra
```

## Resources

### Templates
- [Eisvogel latex template](https://github.com/Wandmalfarbe/pandoc-latex-template)
- [reveal.js](https://revealjs.com/)

### Workflows
- [Chris Krycho](https://v4.chriskrycho.com/2015/academic-markdown-and-citations.html)
- [Robert Talbert](https://rtalbert.org/how-i-wrote-my-book/)
