# How to Compile Correctly

- Make sure that `pdflatex` is installed and in the `PATH`, then open a terminal window and run the command:
```bash
pdflatex Thesis_book.tex
```

- After this we have to run the `biber` command to make sure that the references are loaded correctly.
```bash
biber Thesis_book
```

- Then we run the `pdflatex` command twice for the linking between the bib file and the other files to occur.
```bash
pdflatex Thesis_book.tex
pdflatex Thesis_book.tex
```
