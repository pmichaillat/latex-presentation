# Minimalist LaTeX Template for Academic Presentations

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic presentation. The template uses the [Beamer class](https://github.com/josephwright/beamer). The template follows typographical best practices and has a minimalist design. The template is particularly well suited for research presentations. It is designed to convey scientific arguments and results effectively.

## Documentation

The template is documented at https://pascalmichaillat.org/c/.

## Illustration

The presentation produced by the template can be viewed at https://pascalmichaillat.org/c.pdf.

## Usage

+ Clone the repository to your local machine.
+ Start editing the LaTeX file `presentation.tex` to replace the boilerplate content with the content of your presentation. 
+ Replace the figures in the PDF file `figures.pdf` with the figures that will be included in the presentation (one figure per page).
+ Compile `presentation.tex` with pdfTeX. This will generate a new PDF file named `presentation.pdf`.
+ The LaTeX style file `presentation.sty` formats the presentation. It must be included in the same folder as `presentation.tex`. It can be modified to alter the presentation's format.
+ The file `presentation.pdf` is not required to use the template. It only illustrates the output of the template. It will be overwritten when `presentation.tex` is compiled.

## Software

+ The template was developed with TeX Live 2023 on macOS. 
+ Other LaTeX distributions and operating systems may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/latex-math/issues) to help improve compatibility.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Real-world implementations

+ [Beveridgean Phillips Curve](https://pascalmichaillat.org/15p.pdf)
+ [Modeling Migration-Induced Unemployment](https://pascalmichaillat.org/14p.pdf)
+ [u* = √uv: The Full-Employment Rate of Unemployment in the United States](https://pascalmichaillat.org/13p.pdf)
+ [An Economical Business-Cycle Model](https://pascalmichaillat.org/7p.pdf)
+ [Beveridgean Unemployment Gap](https://pascalmichaillat.org/9p.pdf)
+ [Pricing under Fairness Concerns](https://pascalmichaillat.org/8p.pdf)
+ [Resolving New Keynesian Anomalies with Wealth in the Utility Function](https://pascalmichaillat.org/11p.pdf)

## Related resources

+ [latex-paper](https://github.com/pmichaillat/latex-paper) - This LaTeX template produces academic papers following the same typographic principles and with a similar appearance as this presentation template. 
+ [latex-math](https://github.com/pmichaillat/latex-math) - These LaTeX commands simplify writing mathematical expressions. They can be used in combination with this presentation template.