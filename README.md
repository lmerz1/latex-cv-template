
# My LaTeX "CV"* template

This is a TeX-based remake of various templates and recommendations
I've encountered and used for myself over the years,
in hopes that it'll be useful to someone. :-)

If you're new to the world of LaTeX/TeX, I can highly recommend Matt Kline's
[Modern LaTeX](https://bitbashing.io/modern-latex)
([PDF](https://assets.bitbashing.io/modern-latex.pdf)).

## Design goals

- Looks nice
- Maximize use of the available space for job experience entries and the bullet
  points within those (aim for one-pager!)
- Minimal setup; know the reason of inclusion for every package in the preamble
- Enable the template to be adapted easily for German-language CVs


## Usage

1. Fill in your personal data in the section near the top, then populate the
education, job, and other entries where applicable.
2. Change locale of the `babel` package, currently in line 72 of the source
text, if your CV is not intended to be used in a German-speaking environment.
This controls the format of the date that is added at the bottom.
3. Comment out old entries or even entire sections (like e.g. extracurricular
activity) depending on how relevant the information is to each application.
No more multiple CV file copies for every application!
Just export to PDF (see next step) and (un-)comment entries again when you're done.
4. Compile using `xelatex` (i.e., `xelatex cv.tex` on the command line), which is
available with your local LaTeX installation.
(For example on macOS, the engine will be included with `brew install texlive`.)
It will _probably_ also work just fine with another engine like `pdflatex`,
but I haven't particularly tested that.


If you encounter any mistakes or difficulties, do let me know!

<hr>

*Note: This is technically a résumé and not a _curriculum vitae_
since entries are meant to be commented out once you accumulate more than
what fits onto one page,
but "CV" rolls of the tongue easier and is less characters to type.

