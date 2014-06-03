CCRMA Beamer Theme
==================
- Author:     Jorge Herrera
- Created:    12/12/12 (and checked on 12/13/12, to verify that the world didn't end)

## What's this?

This is a theme to create *LaTeX-Beamer* presentations using [CCRMA][7] (Center for Computer Research in Music and Acoustics at Stanford University) colors and logos.

The idea is to facilitate the use of beamer for high-quality academic presentations. My main goal is to generate PDF presentations, which are portable and cross-platform.

## Multimedia in the generated PDF

*Beamer* includes the `multimedia` package, which allows to display audio and video in PDF files, but the `\sound` command  relies on `pdflatex` or `lualatex` to generate the PDF (not `dvips` + `ps2pdf`). For more details, see the [Beamer user guide][1] (last time I checked it was sections 14.1 and 14.2)

As you can read on the [Beamer user guide][1], embedding multimedia in a PDF is part of the PDF standard. That said, not every PDF viewer handles this feature. In fact, apparently only Adobe's Acrobat Reader is capable of doing that (I've successfully tested it), but we should expect other viewers to eventually include this capability.

## Resources

- The icons used for the multimedia reproduction were obtained from the [Milky icon set][4]
- The audio file used to illustrate multimedia reproduction was obtained from [Freesound.org][5]
- Stanford logo was obtained from Stanford's [Identity Toolkit][6]
- CCRMA logo was obtained from Carr (thanks man!)

## Extending the template

All you could possibly need to modify or create a beamer template can be found at the [Beamer user guide][1].

Another great resource, less comprehensive but extremely clear and addressing all the main issues can be found [here][2]).

Finally, a great beamer theme cheat-sheet can be found [here][3].


## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CCRMA Beamer Theme</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/jorgehatccrma/ccrma-beam" property="cc:attributionName" rel="cc:attributionURL">Jorge Herrera</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.


[1]: http://www.tex.ac.uk/CTAN/macros/latex/contrib/beamer/doc/beameruserguide.pdf  "Beamer user guide"
[2]: http://www.math.umbc.edu/~rouben/beamer/                                       "Simple Beamer Overview"
[3]: http://www.cpt.univ-mrs.fr/~masson/latex/Beamer-appearance-cheat-sheet.pdf     "Beamer Cheat-sheet"
[4]: http://www.iconeden.com/icon/milky-a-free-vector-iconset.html                  "Icons"
[5]: http://www.freesound.org/                                                      "Freesound.org"
[6]: http://identity.stanford.edu/                                                  "SU Identity Toolkit"
[7]: http://ccrma.stanford.edu/                                                     "CCRMA"