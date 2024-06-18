# Novel Template

A Novel template for latex.

## About this repository

This is a template for writing novels. Use it as a starting point, and modify it 
according to your needs.

## Requirements
We recommend using the following tools:

* A Latex Compiler
  * MikTex (Windows)
  * TexLive (Linux)
  * MacTex (MacOS)
* Perl (For Windows)
* Visual Studio Code
  * Latex Workshop Extension
  * Latex Language Support Extension
  * Latex Utilities Extension

## File Structure

### Front Matter

- `frontmatter/blurb.tex`: Contains the blurb of the book.
- `frontmatter/dedication.tex`: Contains the dedication of the book.
- `frontmatter/acknowledments.tex`: Contains the acknowledgments of the book.
- `frontmatter/epilogue.tex`: Contains the epilogue of the book.

### Main Matter

- `metadata.tex`: Contains the metadata of the book (author, title, etc).
- `chapters.tex`: Contains the chapters of the book. List here the files of the chapters. They are included in the order they are listed here.
- Chapter Files: Each chapter is a separate `.tex` file. They should be included in the `chapters.tex` file. `chapters/example.tex` has been included as an example.

## Developer files

- `book.tex`: Main file to generate the PDF of the book. You can change the order of the front matter, main matter, and back matter here.
- `style.sty`: Style file for the book. Change the fonts, headers, footers, asterism, etc. here.
- `/fonts`: Contains the fonts used in the book.

## Exporting to PDF
Use the xelatex recipe to export the book to PDF. You can use the `book.tex` file to generate the PDF.