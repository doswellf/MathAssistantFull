MathAssistant Notes:

This repository is young and incomplete.

This readme file and other supporting and tutorial documents will be added as the math and the code
projects that feed it progress. This document will also contain tips for new users of maxima,SageMath,
Octave, and the jupyter notebook ecosystems as I work through learning how to actually use maxima to
deal with Computational Electromagnetics and other advanced topics.

I have pulled together the code for maxima, sage and collected relevant jupyter notebooks
used to figure out how jupyter notebooks, sage notebooks and maxima-jupyter work.

Thanks to Robert Dodier for help with installation of maxima-jupyter, and for letting me know about JupyterBook.
Thank you to Richard Fateman and the other members of the maxima discussion list for help with maxima itself.

A JupyterBook project is not yet part of this repository although I have built the template book and published on
github pages as a side-effect of pushing my project from my computer to the main branch of my github repository.

You get publishing to github pages automatically using JupyterBook when you push the project to github. If you aren't
familiar with github, I recommend downloading git and using it for small projects manually first. Then you'll understand how
to work with JupyterBook and git together. 

To run jupyter notebooks outside of SageMath I recommend the Anaconda3 installation - it is complete and runs jupyter
out-of-the-box. I haven't checked but am hoping they also have a channel for JupyterBook, a complete publishing and 
deployment package that uses github to host code and it's website.

To run SageMath, just download the latest version for your platform and put it in your home directory. You can add the 
path to your .bashrc in linux. SageMath on Windows likely has an installer but they have multiple installation options.

To run sagetex you must have a complete latex installation (texlive works) and copy the sagetex.sty file from a

$SAGE_HOME/local/share/texmf/tex/latex/sagetex/sagetex.stY ~/texmf

where SAGE_HOME is the top-level directory of the sage installation.

I don't recommend using the ubuntu or other vendor's SageMath, because they're usually out of date (especially sagetex).

To run maxima-jupyter you must have a maxima built over SteelBank Common Lisp as a core image, not a binary executable.

To get maxima-jupyter and installation instructions go to https://github.com/robert-dodier/maxima-jupyter
For further support you can find the maxima-discuss mailing list on the web from the maxima homepage
http://maxima.sourceforge.net/ on the bottom righthand side of the page under Mailing Lists

You must also have a python3 installation with working jupyter notebooks. Installation of JupyterBook is highly recommended if
want to publish your work to pdf or to a website. Again, you can install your system's python3 and pip to run jupyter, 

Or you can install Anaconda3 for a fully supported python3 with the conda environment manager and access to a huge number 
of known working python libraries. I recommend Anaconda3 for people that aren't IT experts.

