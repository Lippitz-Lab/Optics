 [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]  
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].


[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg


# Lecture notes 'Optics'

These are my lecture notes on optics, in our Physics BSc program. I follow the circular structure of Saleh and Teich: Fundamentals of Photonics. We start with geometric rays and Gaussian beams, then discuss scalar waves and Fourier optics. Materials come together with Maxwell's equations and polarization optics. We compare different types of interferometers and coherence as a prerequisite for interference. The lecture concludes with a brief look at quantum optics.

I want you to be able to really do optics, i.e. not only solve textbook problems, but also build setups and do experiments. To this end, the script contains practical sections on alignment procedures and experiments. More details, including 'bookcast' type videos, are available on the [website](https://www.ep3.uni-bayreuth.de/en/teaching/MO/index.html).


The lecture notes are typeset using the LaTeX class ['tufte-book'](https://tufte-latex.github.io/tufte-latex/) by Bil Kleb, Bill Wood, and Kevin Godby, which approximates the work of [Edward Tufte](https://www.edwardtufte.com/). I applied many of the modifications introduced by Dirk Eddelbuettel in the ['tint'](https://dirk.eddelbuettel.com/code/tint.html}) R package. For the time being, the source is LaTeX, not markdown.

## Structure of the repository

The chapters are individual tex-files in the directory tree and included in the main tex file. Figures are mostly made by tikz. Tikz-external is used to save compilation time. It generates pdfs in the figures tree. Some chapters contain handout material for exercises, which is in the handout subdirectory of the chapter.
