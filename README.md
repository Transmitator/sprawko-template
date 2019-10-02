# *Sprawko* template

A simple lab report template I used to use. 🎓

This is based on this [template](https://www.overleaf.com/latex/templates/praca-dyplomowa-politechnika-slaska-aei-szablon/vttgfpfypfmk).

## Some cool things that made my life easier

### todonotes
Cool package for adding comments, annotations and stuff. 
*Worth remembering:*
- `disable` option in preambule makes all **todonotes** become invisible.
- `\listoftodos` - create a list of all **todonotes**
- `\missingfigure` - creates a temporary figure. I'm using it inside `figure` 
whenever I have not yet prepared the final graph, image, etc.
- [Check out the docs](https://mirror.hmc.edu/ctan/macros/latex/contrib/todonotes/todonotes.pdf)

### listings
Listing whole file:
```tex
\lstinputlisting{../folder/file.py}
```
Simple code snippet inside a `*.tex` document:
```tex
\begin{lstlisting}
% Put your code here
\end{lstlisting}
```
Find more in
[docs](http://texdoc.net/texmf-dist/doc/latex/listings/listings.pdf)
or on [wiki](https://en.wikibooks.org/wiki/LaTeX/Source_Code_Listings).

### Lots of other stuff...
> Perhaps I will describe it later 🤫

## Editor

Some useful _magic comments_ from **TexStudio**:

* % !TeX spellcheck = en_GB
* % !TeX encoding = UTF-8


