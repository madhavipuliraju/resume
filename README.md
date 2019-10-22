* Introduction
  This repository contains my updated profile written in
  =LateX=

* How to build profile ??
** Pre requisites for Ubuntu/Debian
   
#+BEGIN_EXAMPLE
sudo apt-get install texlive-full
#+END_EXAMPLE
** Steps
  1. Clone the repository & change directory
     #+BEGIN_EXAMPLE
     git clone https://github.com/madhavipuliraju/resume.git
     cd resume
     #+END_EXAMPLE
  2. Compile the =.tex= files
     #+BEGIN_EXAMPLE
     pdflatex madhavi.tex
     #+END_EXAMPLE
  3. Above step(3) should generate =resume.pdf= file
