
# Z1
README.md
========================================================
Z.1: Financial Accounts of the United States
--------------------------------------------------------

### About:

[Financial Accounts of the United States - Z.1](https://www.federalreserve.gov/releases/z1/current/default.htm): 

The Board of Governors of the Federal Reserve System
releases the Financial Accounts of the United States,
refered to as "Z.1".
The Financial Accounts of the United States includes data on
the flow of funds and levels of financial assets and liabilities,
by sector and financial instrument;
full balance sheets, including net worth,
for households and nonprofit organizations,
nonfinancial corporate businesses, and nonfinancial noncorporate businesses;
Integrated Macroeconomic Accounts; and
additional supplemental detail.

I intend to use this data to build a model of the US economy here.

### Contents of the Z1 Repository:

### Tools Used:

I use TeXstudio and ReText, with noweb and R, on the ubuntu mate operating system:

To compile the noweb .nw files I use this user command in TeXstudio:

```
noweb %.nw | pdflatex -synctex=1 -interaction=nonstopmode %.tex
```

To compile the knitr .Rnw files I use this user command in TeXstudio:

```
Rscript -e "library(knitr);knit('%.Rnw')" | pdflatex -synctex=1 -interaction=nonstopmode %.tex
```

### Web References:

* [Board of Governors of the Federal Reserve System](https://www.federalreserve.gov/default.htm)

