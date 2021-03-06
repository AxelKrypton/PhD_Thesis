# PhD Thesis

This is my Ph.D. Thesis, that was completed at J. W. Goethe Universität (Frankfurt am Main) in 2016.
I decided to add it to GitHub to provide an up-to-date version of it.
Here you may find some differences with respect to other copies present on the web.
Please refer to [this file](Sciarra_Thesis_digital.pdf) as most recent version of the thesis.

**Title:** *«The QCD phase diagram at purely imaginary chemical potential from the lattice»*

## Additional information
A few *TeX*nical comments about the graphical layout of the Thesis.
I did not decide to use some fancy latex class and I simply customized the `book` one in few aspects.
- The [pgf](https://www.ctan.org/pkg/pgf) package was intensively used, even though some pictures were manually drawn with [Inkscape](https://inkscape.org/en/).
- The chapter/section title layout was customized using the [titlesec](https://www.ctan.org/pkg/titlesec) package, together with TikZ and [pgfornament](https://www.ctan.org/pkg/pgfornament).
- The package [tocloft](https://www.ctan.org/pkg/tocloft) was used to customize the table of content layout.
- The Bibliography was typeset using the [biblatex](https://www.ctan.org/pkg/biblatex) package. Some (quite heavy) modification was done in order to obtain the desired result (main resource: [biblatex manual](http://mirrors.ctan.org/macros/latex/contrib/biblatex/doc/biblatex.pdf)).
- During the writing phase, the [todonotes](https://www.ctan.org/pkg/todonotes) package turned out to be extremely useful.
- To typeset my Curriculum Vitae, the [moderncv template](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter) was used with minor modifications.

### External links
[Here](https://github.com/AxelKrypton/Goethe_University_PhD_thesis_bureaucracy), you can find the TeX code for the title page (together with some useful information if you are a Ph.D. student at J. W. Goethe Universität in Frankfurt).

### Citing the thesis
If you wish to cite this thesis in any of your work, feel free to do it.
A possibility for your bibTeX entry could look like in the following.
Of course, you could use the [biblatex](https://www.ctan.org/pkg/biblatex) package to customize your bibliography layout.
```
@phdthesis{sciarra,
    Title       = {The QCD phase diagram at purely imaginary chemical potential from the lattice},
    Author      = {Sciarra, Alessandro},
    Institution = {{Johann Wolfgang Goethe Universit\"at}},
    Location    = {{Frankfurt am Main}},
    Year        = {2016},
    Pages       = {209},
    Url         = {https://github.com/AxelKrypton/PhD_Thesis}
}
```
