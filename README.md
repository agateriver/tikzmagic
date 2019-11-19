# tikzmagic

A Jupyter extension for compiling and displaying images described by the [TikZ](http://www.texample.net/tikz/) language.

## Requirements

- IPython/Jupyter
- LaTeX (`xelatex`)
- ImageMagick
- Ghostscript

assure xelatex, magick and ghostscript binary in your path.

## Installation

```pip install git+git://github.com/agateriver/tikzmagic.git```

## Usage

In an iPython notebook cell: `import tikzmagic` or `%load_ext tikzmagic`.

## Optional arguments

- `-p` or `--latex_packages`
- `-x` or `--latex_preamble`
- `-l` or `--tikz_libraries`
- `-i` or `--input_file`
- `-s` or `--scale`, default=1 (corresponding to 300dpi)
- `-b` or `--border`, default=4

## Example

[Example iPython notebook](example.ipynb)
