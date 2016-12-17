# Contract for freelance front-end development work

This is the contract my clients sign for any freelance front-end web development work.
It is written using LaTeX and is based on the [Contract Killer](https://gist.github.com/malarkey/4031110) by Andy Clarke.

## Instructions for usage

1. Replace variables such as your name and contact information. For example, I would replace `\newcommand{\freelancerName}{[freelancer name]}` with `\newcommand{\freelancerName}{Chafic Najjar}`.
2. Replace the image `images/signature.png` with an image of your own signature.
3. Compile.

## Prerequisites

You need to install:

+ [LaTeX](http://www.latex-project.org/).
+ [XeLaTeX](http://www.xelatex.org/).
+ The font [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro).
+ The required LaTeX packages.

## Compilation

To compile:

```
xelatex sample-contract.aux
```

This will generate the PDF file `sample-contract.pdf` that you can send to your client.

## License and Credits

Created by [Chafic Najjar](https://github.com/chaficnajjar) and is licensed under the MIT license.
