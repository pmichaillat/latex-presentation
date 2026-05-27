# Minimalist LaTeX Template for Academic Presentations

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic presentation. The template uses the [Beamer class](https://github.com/josephwright/beamer). The template follows typographical best practices and has a minimalist design. The template is particularly well suited for research presentations. It is designed to convey scientific arguments and results effectively. The repository also contains a variant of the template to create a wide, 16:9 presentation.

## Documentation

The template is documented at https://pascalmichaillat.org/c/.

## Illustration

The presentation produced by the template can be viewed at https://pascalmichaillat.org/c.pdf. The 16:9 presentation can be viewed at https://pascalmichaillat.org/cw.pdf.

## Usage

- Clone the repository to your local machine.
- Start editing the LaTeX file `presentation.tex` to replace the boilerplate content with the content of your presentation. 
- Replace the figures in the PDF file `figures.pdf` with the figures for your presentation (one figure per page).
- Compile `presentation.tex` with pdfTeX. This will generate a new PDF file named `presentation.pdf`.
- The LaTeX style file `presentation.sty` formats the presentation. It must be included in the same folder as `presentation.tex`. It can be modified to alter the presentation's format.
- The file `presentation.pdf` is not required to use the template. It only illustrates the output of the template. It will be overwritten when `presentation.tex` is compiled.

To produce a wide presentation with 16:9 aspect ratio, edit the LaTeX file `wide.tex` instead of `presentation.tex` and follow the same steps. The wide presentation uses the same `presentation.sty` and `figures.pdf` files. Compiling `wide.tex` with pdfTeX writes `wide.pdf`.

## Software

- The template is currently operational with TeX Live 2025 on macOS.
- Other LaTeX distributions and operating systems may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/latex-presentation/issues) to help improve compatibility.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Real-world implementations

- [Recession Detection Using Classifiers on the Anticipation-Precision Frontier](https://pascalmichaillat.org/17p.pdf) (by P. Michaillat)
- [Does Skill Abundance Still Matter? The Evolution of Comparative Advantage in the 21st Century](https://www.shinnosuke-kikuchi.com/files/research/slide-KIKUCHI-skill-trade.pdf) (by S. Kikuchi)
- [Efficient range estimation with NDB interpreted code](https://dydra.com/data/els2026/els-2026-retzlaff-efficient-range-estimation-with-ndb-ic_slides_20260522T154456-CEST_published__d55fc286.pdf) (by M. Retzlaff)
- [A Lisp dialect for NDB interpreted code](https://dydra.com/data/els2026/els-2026-retzlaff-a-lisp-dialect-for-ndb-ic_slides_20260522T154456-CEST_published__d55fc286.pdf)  (by M. Retzlaff)
- [Beveridgean Phillips Curve](https://pascalmichaillat.org/15p.pdf) (by P. Michaillat and E. Saez)
- [Modeling Migration-Induced Unemployment](https://pascalmichaillat.org/14p.pdf) (by P. Michaillat)
- [u* = √uv: The Full-Employment Rate of Unemployment in the United States](https://pascalmichaillat.org/13p.pdf) (by P. Michaillat and E. Saez)
- [An Economical Business-Cycle Model](https://pascalmichaillat.org/7p.pdf) (by P. Michaillat and E. Saez)
- [Beveridgean Unemployment Gap](https://pascalmichaillat.org/9p.pdf) (by P. Michaillat and E. Saez)
- [Pricing under Fairness Concerns](https://pascalmichaillat.org/8p.pdf) (by E. Eyster, K. Madarasz, and P. Michaillat)
- [Resolving New Keynesian Anomalies with Wealth in the Utility Function](https://pascalmichaillat.org/11p.pdf) (by P. Michaillat and E. Saez)


## Related resources

- [latex-paper](https://github.com/pmichaillat/latex-paper) - This LaTeX template produces academic papers that follow the same typographic principles as the presentation template. 
- [latex-book](https://github.com/pmichaillat/latex-book) - This LaTeX template produces lecture notes and academic books that follow the same typographic principles as the presentation template. 
- [latex-math](https://github.com/pmichaillat/latex-math) - These LaTeX commands simplify writing mathematical expressions. They can be used in combination with the presentation template.
- [matlab-figures](https://github.com/pmichaillat/matlab-figures) - This MATLAB template produces minimalist scientific figures that can be inserted into your presentation.