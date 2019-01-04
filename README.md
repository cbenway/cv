# Christopher Benway's curriculum vitae

My C.V. can be viewed and downloaded at <https://github.com/cbenway/cv/blob/master/cv.pdf>.

## Creating the PDF

On Ubuntu install these packages:

~~~~{.bash}
sudo apt-get update
sudo apt-get install texlive texlive-latex-extra
~~~~

On OS X, install [MacTeX](http://www.tug.org/mactex/).

The `to_pdf.sh` script will create the final PDF.

~~~~{.bash}
to_pdf.sh cv.tex
~~~~

The code used to generate this C.V. was written by [Dave Tang](https://github.com/davetang).
