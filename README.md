# wiki-looper

This program takes input in the form of a wikipedia web page and that page,
then follows the first link of every paragraph of every next page until the
series of pages completes a loop.


Requires:

5.010;

LWP::Simple;

Getopt::Long;


```perl
$  ./wiki-looper -h

  This program takes input in the form of a wikipedia web page and that page,
  then follows the first link of every paragraph of every next page until the
  series of pages completes a loop.

    Basic Usage: ./wiki-looper "Page Name"

  Options:

    -help       Print this help.

  Examples:

    # show the available colors
    ./wiki-looper "Bleu cheese"


```
