# muddy-thesis: tufte-inspired MIT thesis template

This repository is named after the on-campus bar at MIT, _The Muddy_, in honor of all the thesis writing I would have done there if COVID-19 was not a thing. Accordingly, the styling (formatting, page numbers, coverpage) are appropriate for an MIT thesis. I found the provided MIT thesis template _too automated_ with comments and switches galore; this version automates only the most universal parts and lets the user manually input the details. Check the [MIT specifications for thesis formatting](https://libraries.mit.edu/distinctive-collections/thesis-specs/#format) to ensure you have the correct formatting for your graduation scenario (and congratulations!).

Everything is based on [`KOMA-script`](https://ctan.org/pkg/koma-script?lang=en), so it is easy to make changes as you wish.

This repository is based off amazing work from:
- [Pseudomanifold/latex-mimosis](https://github.com/Pseudomanifold/latex-mimosis)
- [andythomas/TeX-sidenotes](https://github.com/andythomas/TeX-sidenotes)

And inspired by the design principles (and books) of Edward Tufte: minimal, functional, and elegant.

## how to use
- There are three branches of this repo:
  - main = citations are footnotes, figures default to full width
  - partial = citations are sidenotes but pages are full margin unless sidenotes/sidefigures are used
  - sidenotes = most Tufte-like, wide margin for citations, figures, etc
- This repo is fashioned as a template; to best use, log in with your GitHub account and click `use this template`
- To build, simply type `make build`
- To clean, simply type `make clean`
- Write your thesis :)

Personal preference: I use Sublime with the LaTeXing package. There are several help guides online to set this up correctly depending on your operating system.

## license

The template uses the MIT license. All software is "as is".
