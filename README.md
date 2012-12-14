CCRMA Beamer Theme
==================
- Author:     Jorge Herrera
- Created:    12/12/12 (and checked on 12/13/12, to verify that the world didn't end)

## What's this?

This is a theme to create *LaTeX-Beamer* presentations using CCRMA (Center for Computer Research in Music and Acoustics at Stanford University) colors and logos.

The idea is to facilitate the use of beamer for high-quality academic presentations. It should be noted that my main goal is to generate PDF presentations, which are portable and cross-platform.

## Multimedia in the generated PDF

*Beamer* includes the `multimedia` package, which allows to display audio and video in PDF files, but the `\sound` command  relies on `pdflatex` to generate the PDF (not `dvips` + `ps2pdf` or other tools). For more details, see the [Beamer user guide](http://www.tex.ac.uk/CTAN/macros/latex/contrib/beamer/doc/beameruserguide.pdf) (last time I checked it was sections 14.1 and 14.2)

As you can read on the [Beamer user guide](http://www.tex.ac.uk/CTAN/macros/latex/contrib/beamer/doc/beameruserguide.pdf), embedding multimedia in a PDF is part of the PDF standard. That said, not every PDF viewer handles this feature. In fact, apparently only Adobe's Acrobat Reader is capable of doing that (I've successfully tested it), but we should expect other viewers to eventually include this capability.

## Resources

- The icons used for the multimedia reproduction were obtained from the [Milky icon set](http://www.iconeden.com/icon/milky-a-free-vector-iconset.html)
- The audio file used to illustrate multimedia reproduction was obtained from [Freesound.org](http://www.freesound.org/)
- Stanford logo was obtained from Stanford's [Identity Toolkit](http://identity.stanford.edu/)
- CCRMA logo was obtained from Carr (thanks man!)
