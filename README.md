# Document Templates


- [Presentations](beamer/default_beamer.tex)
- [Articles](article/default_article.tex)
- [CV/resume](cv/default_cv.tex)


## Other tools

- https://www.doi2bib.org/
- Use `latexmk` to run things.

```sh
latexmk -silent -cd -gg -pdflua -view=pdf -pvc -pvctimeout --synctex=16 filename.tex
```
