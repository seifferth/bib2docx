# bib2docx

`bib2docx` is a simple shell script that uses [pandoc](https://pandoc.org)
and pandoc-citeproc to convert biblatex files to docx.

## Usage

```
Usage: bib2docx [options] <files>

Options:
      --title     Title for the output bibliography
      --author    Author of this bibliography (may be specified
                  multiple times for multiple authors)
      --date      Date for the output bibliography
      --lang      Specify a language for the output bibliography
      --csl       Citation style to use in output bibliography
  -o  --output    Specify a name for the output file
  -h  --help      Print this help message and exit
```

## Installing

Simply save `bib2docx` in some directory included in your `PATH`, mark
it as executable and make sure all dependencies are satisfied.

## Dependencies

- [pandoc](https://pandoc.org)
- [pandoc-citeproc](https://pandoc.org) (may already be included with
  pandoc in some distributions)
