# travis_lyx_to_epub

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_lyx_to_epub.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_lyx_to_epub) (should fail)

Minimal project that converts a LyX document that is converted to PDF and is tested by Travis CI.

This project does not and connot work, because LyX cannot convert to EPUB directly. Use [travis_pandoc_lyx_to_epub](https://github.com/richelbilderbeek/travis_pandoc_lyx_to_epub) instead,
which lets LyX create a TeX file, then uses `pandoc` to convert to EPUB.

This GitHub is part of [the Travis Tutorial](https://github.com/richelbilderbeek/travis_tutorial)

## More specific setup

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_pandoc_lyx_to_epub.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_pandoc_lyx_to_epub) [travis_pandoc_lyx_to_epub](https://github.com/richelbilderbeek/travis_pandoc_lyx_to_epub): use `pandoc` to convert a LyX file to EPUB

## Less complex setups

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_lyx.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_lyx) [travis_lyx](https://github.com/richelbilderbeek/travis_lyx): convert a LyX file to PDF
