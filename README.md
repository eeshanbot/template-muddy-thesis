# muddy-thesis: tufte-inspired MIT thesis template

This repository is named after the on-campus bar at MIT, _The Muddy Charles Pub_, lovingly called _The Muddy_, in honor of all the thesis writing I would have done there if COVID-19 was not a thing. Accordingly, the styling (formatting, page numbers, coverpage) are appropriate for an MIT thesis. Everything is based on [`KOMA-script`](https://ctan.org/pkg/koma-script?lang=en), so it is easy to make changes as you wish.

This repository is based off amazing work from:
- [Pseudomanifold/latex-mimosis](https://github.com/Pseudomanifold/latex-mimosis)
- [andythomas/TeX-sidenotes](https://github.com/andythomas/TeX-sidenotes)

And inspired by the design principles (and books) of Edward Tufte: minimal, functional, and elegant.

## how to use
- There are three branches of this repository
  - main = citations are footnotes, figures default to full width
  - partial = citations are sidenotes but pages are full margin unless sidenotes/sidefigures are used
  - sidenotes = most Tufte-like, wide margin for citations, figures, etc
- Clone this repository
- Start your own repository
- Use the Makefile provided --- `make build` --- to compile



## license

The template uses the MIT license.
