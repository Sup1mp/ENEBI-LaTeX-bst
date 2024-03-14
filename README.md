# ENEBI-LaTeX-bst
I just modified the [plainnat.bst](https://github.com/mrterry/latex_files/blob/master/texmf/tex/latex/natbib/plainnat.bst) and the [abntex2-alf.bst](https://github.com/abntex/abntex2/blob/master/bibtex/bst/abntex2/abntex2-alf.bst) to make a file that works with natbib and follows the ABNT rules desired by ENEBI from Brazil.

## How to use
1. Download the `.bst` file and put it on your document folder
2. Use the natbib package `\usepackage{natbib}`
3. Use `\bibliographystyle{4enebi}` in your document

   This should make it work. It's not complete yet, but gets the job done for now.
