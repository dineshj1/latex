my latex templates

# dirs

* media: everything that is not a tex file, such as an image or table
* _aux: auxiliary tex compilation files.
* _out: output files such as pdf

while using those two directories adds some complexity to compilation,
they clear up the main dir so much that I decided to use them anyways

To easily compile while keeping this directory structure, use:

    ./latex-to-pdf main.tex

# files

## template.tex

when starting new projects, copy this template

## main.tex

cheatsheet of lots of latex commands

## main.sty

both cheatsheet and template for new projects

## table.ods

it is much easier to edit tables in [libreoffice](http://www.libreoffice.org/features/calc/)
or other spreadsheet applications since its much easier to keep things alligned

give a lable to every table, and then name the tables as label.ods so that 
corresponding tables can be found afterwards for further editing

# THANKS

* .gitignore from https://raw.github.com/gist/149016/e056704ebab0fbcd7bf937169b4057d378d09cf8/.gitignore

# TODO

* write latex-to-pdf in python

* how to add hrule after environments

* how to create theorem environments with label (bold Theorem thing at beginning)
    given in source and not in definition

* how to center all rows in a tabular without specifying how many rows are there
    ([c] instead of [ccccc], which might change afterwards)
