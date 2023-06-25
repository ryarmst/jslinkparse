# jslinkparse

A simple Python 3 script to organize JS Link Finder (Burp Extension) output for further testing. 
NOTE: probably does not handle some edge cases well.

## Usage

usage: jslinkparse.py [-h] infile

positional arguments:
  infile      Input file

optional arguments:
  -h, --help  show this help message and exit

## Resources

This tool consumes output from JS Link Finder - a tool based on LinkFinder. You may find you prefer output straight from LinkFinder, but you won't get direct Burp integration.

- [JS Link Finder](https://github.com/PortSwigger/js-link-finder)
- [LinkFinder](https://github.com/GerbenJavado/LinkFinder)

## TODO

If I ever have time, I might just fork the extension and expand the sorting options in Burp.
