# train-emergency-light-driver

Lights driver for "Service, Test and Developing Train". Depending on train type, different LEDs colors can be used.

## Lights:
 - Front and Rear – disable / both train directions / all on
 - Outline marker lights – disable / alternately blinking / alternately fading / all on
 - Top emergency lights – disable / enable

## Branches
 - `master` - Description
 - `code` - Code
 - `doc` - Documentation in LaTeX
 - `hardware` - Arduino configuration for Atmega328 8MHz

## Check submodule's READMEs
Some submodules may contain requirements for successful running.

## doc - how to run

Requirements:
 - https://www.tug.org/mactex/
 - http://www.tug.org/fonts/getnonfreefonts/

Command to build documentation:
```
pdflatex -synctex=1 -interaction=nonstopmode Documentation.tex
```

