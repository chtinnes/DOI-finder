DOI finder

This is a fork of [torfbolt/DOI-finder](https://github.com/torfbolt/DOI-finder). The script has been adapted to Python3 and some fixes were made to adapt to newer versions of used libraries, as well as APIs.

This is a short python script to faciliate the addition of Digital Object Identifier (DOI) entries to an existing bibtex .bib database. It uses the sites http://www.crossref.org/ and http://www.google.com/ to find the DOI of a bibliographic entry. Found DOIs are added to the bibtex database automatically or after manual confirmation, depending on the probability of a correct resolution.

Synax:
src/doi-finder file.bib
