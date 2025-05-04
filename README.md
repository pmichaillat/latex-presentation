# Minimalist LaTeX Template for Academic Presentations

This repository contains a [LaTeX](https://github.com/latex3/latex2e) template to create an academic presentation. The template uses the [Beamer class](https://github.com/josephwright/beamer). The template carefully follows typographical best practices and has a minimalist design. The template is particularly well suited for research presentations. It is designed to convey scientific arguments and results effectively.

## Documentation

The template is documented at https://pascalmichaillat.org/c/.

## Illustration

The presentation produced by the template can be viewed at https://pascalmichaillat.org/d1.pdf.

## Usage

+ Clone the repository to your local machine.
+ Start editing the LaTeX file `presentation.tex` to replace the boilerplate content with the content of your presentation. 
+ Replace the figures in the PDF file `figures.pdf` with the figures that will be included in the presentation. There should be one figure per page.
+ Compile `presentation.tex` with pdfTeX. This will generate a new PDF file named `presentation.pdf`.
+ The LaTeX style file `presentation.sty` collects all the commands to format the presentation. The file must be included in the same folder as `presentation.tex`. It can be modified to alter the presentation's format.
+ The file `presentation.pdf` is not required to use the template. It only illustrate the output of the template, and will be overridden once `presentation.tex` is compiled.

## Software

The template was developed, tested, and validated on a Mac with the MacTeX-2023 distribution. 

While the template should also work on other operating systems and with other LaTeX distributions, compatibility cannot be guaranteed. Users on Windows or Linux systems, or those using different LaTeX distributions, may need to make minor adjustments. [Please report](https://github.com/pmichaillat/latex-presentation/issues) any compatibility issues or bugs to help improve cross-platform support.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Real-world implementations

+ [Modeling Migration-Induced Unemployment](https://pascalmichaillat.org/14p.pdf)
+ [u* = √uv: The Full-Employment Rate of Unemployment in the United States](https://pascalmichaillat.org/13p.pdf)
+ [An Economomical Business-Cycle Model](https://pascalmichaillat.org/7p.pdf)
+ [Beveridgean Unemployment Gap](https://pascalmichaillat.org/9p.pdf)
+ [Pricing under Fairness Concerns](https://pascalmichaillat.org/8p.pdf)
+ [Resolving New Keynesian Anomalies with Wealth in the Utility Function](https://pascalmichaillat.org/11p.pdf)

## Related resources

+ [LaTeX template for academic papers](https://github.com/pmichaillat/latex-paper) - This template produces academic papers following the same principles, and with a similar appearance, as this presentation template. 
+ [LaTeX commands to write math](https://github.com/pmichaillat/latex-math) - These commands make it easy to write mathematical expressions. They can be used in combination with this paper template.
