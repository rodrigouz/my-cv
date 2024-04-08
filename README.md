

# My CV [![Example](https://img.shields.io/badge/example-pdf-green.svg)](https://raw.githubusercontent.com/rodrigouz/My-CV/master/resume.pdf)


## What is My CV?
[**My CV**](https://github.com/rodrigouz/my-cv) is LaTeX template for a **CV(Curriculum Vitae)** or **resume** by [Awesome-CV](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv). It is easy to customize your own template, especially since it is really written by a clean, semantic markup.


## Preview
You can see [PDF](https://raw.githubusercontent.com/rodrigouz/My-CV/master/resume.pdf)

![alt tag](https://raw.githubusercontent.com/rodrigouz/My-CV/master/resume.png)


## How to Use
### Requirements

A full TeX distribution is assumed.  [Various distributions for different operating systems (Windows, Mac, \*nix) are available](http://tex.stackexchange.com/q/55437) but TeX Live is recommended.
You can [install TeX from upstream](http://tex.stackexchange.com/q/1092) (recommended; most up-to-date) or use `sudo apt-get install texlive-full` if you really want that.  (It's generally a few years behind.)

Install ImageMagick only if you would like to convet the pdf to image format
`sudo apt-get install imagemagick`

### Usage

At a command prompt, run
```bash
$ xelatex {your-cv}.tex
```
This should result in the creation of ``{your-cv}.pdf``

Convert the pdf to an image format
```bash
convert -density 300 -colorspace RGB  -background white -flatten resume.pdf -quality 100 resume.png
```


## Credit
### LaTeX
LaTeX is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia.

You can find out more about it here: [LaTeX Project](http://www.latex-project.org)

### LaTeX-FontAwesome
[LaTeX FontAwesome](https://github.com/furl/latex-fontawesome) is bindings for FontAwesome icons to be used in XeLaTeX.

### Roboto
[Roboto](https://github.com/google/roboto) is the default font on Android and ChromeOS, and the recommended font for Google’s visual language, Material Design.

### Source Sans Pro
[Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro) is a set of OpenType fonts that have been designed to work well in user interface (UI) environments.


## Contact
You are free to take my `.tex` file and modify it to create your own resume. Please don't use my resume for anything else without my permission, though!

Good luck!
