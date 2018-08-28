Build dependencies:
 - Pandoc	http://pandoc.org/

For html:
	GitHub.html5 template		https://github.com/tajmone/pandoc-goodies		MIT license
	
For PDF
	pdflatex			https://www.tug.org/applications/pdftex/
	eisvogel.latex template		https://github.com/Wandmalfarbe/pandoc-latex-template	BSD License


1. Clone the repository  
2. Install the templates into the Pandoc template directory.  On *nix ~/.pandoc/templates  (Copies of the templates are available within this repository)

To build the html:  
````
$pandoc pandoc --template=GitHub.html5 InputFile.md -o output.html
````

To build the pdf:  
````
pandoc InputFile.md -o example.pdf --from markdown --template eisvogel --listings
````

HTML Screenshot:  
![html-screenshot](html-screenshot.png)

PDF Screenshot:  
![pdf-screenshot](pdf-screenshot.png)

